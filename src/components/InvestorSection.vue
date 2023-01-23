<template>
  <section id="investor">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col cols="12" sm="8" class="white--text text-center">
              
              <h1 class="font-weight-light" justify="center" >
                There are two ways to participate in Bufficorn Ventures.
              </h1>
            </v-col>
          </v-row>
          <v-row align="center" justify="center">
            <v-col cols="6" sm="4" class="white--text text-center">
                <a href="https://ethden.page.link/investBV" target="_new">
                    <v-img src="@/assets/img/KingBuffi.png" class="d-block ml-auto mr-auto" max-width="250px" />
                <p>Investors</p> </a>
            </v-col>
            <v-col cols="6" sm="4" class="white--text text-center">
                <a href="https://ethden.page.link/bvaffiliate" target="_new">
                    <v-img src="@/assets/img/BuffiTank.png" class="d-block ml-auto mr-auto" max-width="250px" />
                <p>Affiliate Members</p> </a>
            </v-col>

          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#investor {
  background-image: url("~@/assets/img/ETH_site_backgrounds_night_1440x515.png");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 500px;
}

#investor .container,
#investor .row {
  height: 100%;
}
</style>