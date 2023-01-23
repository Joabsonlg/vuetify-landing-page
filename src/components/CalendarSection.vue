<template>
  <section class="pb-8" id="calendar">
    <v-container fluid>
    <div
      class="ma-4"
      style="height: 100%"
    >
      <!-- Event details menu -->
      <v-menu
        v-model="selectedOpen"
        :close-on-content-click="false"
        :activator="selectedElement"
        offset-x
      >
        <v-card min-width="200px">
          <v-toolbar
            color="purple accent-4"
            dark
          >
            <v-toolbar-title>
              {{ selectedEvent.name }}
            </v-toolbar-title>
          </v-toolbar>
          <v-card-text>
            <div class="text-center">
              {{ selectedEventStart }}
              to
              {{ selectedEventEnd }}
            </div>
            <v-checkbox
              readonly
              label="All day"
              :value="!selectedEvent.timed"
            >
            </v-checkbox>
          </v-card-text>
        </v-card>
      </v-menu>
      <v-calendar
        :events="events"
        event-color="purple accent-4"
        @click:day="viewDay"
        @click:event="showEvent"
        v-model="focus"
        :type="type"
        now="2022-04-23"
      ></v-calendar>
    </div>
  </v-container>
  </section>
</template>

<script>
import { format } from 'date-fns';

export default {
  name: 'App',
  data: () => {
    return {
      focus: '',
      type: 'month',
      selectedOpen: false,
      selectedElement: undefined,
      selectedEvent: {},
      events: [
        {
          name: 'Event 1',
          start: '2022-04-01',
          timed: false,
        },
        {
          name: 'Event 2',
          start: '2022-04-04',
          end: '2022-04-06',
        },
        {
          name: 'Event 3',
          start: '2022-04-04T05:00:00',
          end: '2022-04-04T07:00:00',
          timed: true,
        },
        {
          name: 'Event 4',
          start: '2022-04-08T08:00:00',
          end: '2022-04-08T10:00:00',
          timed: true,
        },
      ],
    };
  },
  methods: {
    viewDay({ date }) {
      this.focus = date;
      this.type = 'day';
    },
    showEvent({ nativeEvent, event }) {
      const open = () => {
        this.selectedEvent = event;
        this.selectedElement = nativeEvent.target;
        requestAnimationFrame(() =>
          requestAnimationFrame(
            () => (this.selectedOpen = true)
          )
        );
      };

      if (this.selectedOpen) {
        this.selectedOpen = false;
        requestAnimationFrame(() =>
          requestAnimationFrame(() => open())
        );
      } else {
        open();
      }

      nativeEvent.stopPropagation();
    },
  },
  computed: {
    selectedEventStart() {
      return (
        (this.selectedEvent &&
          this.selectedEvent.start &&
          format(
            new Date(this.selectedEvent.start),
            'h:mm a'
          )) ||
        '12:00 AM'
      );
    },
    selectedEventEnd() {
      return (
        (this.selectedEvent &&
          this.selectedEvent.end &&
          format(
            new Date(this.selectedEvent.end),
            'h:mm a'
          )) ||
        '12:00 AM'
      );
    },
  },
};
</script>
﻿