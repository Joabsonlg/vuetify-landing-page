<template>
  <v-footer dark padless>
    <v-card flat tile class="secondary white--text text-center">
      <v-card-text>
        <v-btn
          v-for="(icon, i) in icons"
          :key="i"
          class="mx-4 white--text"
          :href="icon.link"
          target="_blank"
          icon
        >
          <v-icon size="24px">{{ icon.text }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        A member of the <a href="https://sporkdao.org">SporkDAO</a> community.
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>Copyright Bufficorn Ventures 2023</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<style scoped>
.v-card {
  width: 100%;
}
</style>

<script>
export default {
  data: () => ({
    icons: [
      {
        text: "mdi-twitter",
        link: "https://twitter.com/BufficornV",
      },
      {
        text: "mdi-linkedin",
        link: "https://www.linkedin.com/company/bufficorn-ventures",
      },
      {
        text: "mdi-mail",
        link: "emailto:info@bufficorn.ventures",
      },

    ],
  }),
};
</script>
