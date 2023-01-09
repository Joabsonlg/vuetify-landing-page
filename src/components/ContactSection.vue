<template>
  <section class="pb-8" id="contact">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row justify="center">
            <v-col cols="12" sm="5">
              <h1 class="font-weight-light display-1">Contact Us</h1>
              <h3 class="font-weight-light mt-3">
                We are always looking for partners, potential portfolio companies, and community memebers.
              </h3>
              <h3 class="font-weight-light mt-3">
                Apply to <a href="https://ethden.page.link/apply">become a BV company</a>
              </h3>
              <h3 class="font-weight-light">
                Email us <a href="emailto:&#105;&#110;&#102;&#111;&#064;&#098;&#117;&#102;&#102;&#105;&#099;&#111;&#114;&#110;&#046;&#118;&#101;&#110;&#116;&#117;&#114;&#101;&#115;">&#105;&#110;&#102;&#111;&#064;&#098;&#117;&#102;&#102;&#105;&#099;&#111;&#114;&#110;&#046;&#118;&#101;&#110;&#116;&#117;&#114;&#101;&#115;</a>
              </h3>
              <h3 class="font-weight-light">
                Signup for our mailing list:<a href="https://ethden.page.link/kmitl">Mailing List</a>
              </h3>
            </v-col>
            <v-col cols="12" sm="5">
              <h1 class="font-weight-light display-1">Become a BV Sponsor</h1>
              <h3 class="font-weight-light mt-3">
                Sponsorship via an <stong>Affiliate Membership</stong> may present advantages for funds, platforms, investment syndicates, and foreign nationals who cannot invest in funds directly.
              </h3>
              <h3 class="font-weight-light mt-3">
                <a href="https://ethden.page.link/bvaffiliate">Become a BV Affiliate Member</a>
              </h3>

            </v-col>


          </v-row>
        </v-col>
      </v-row>
    </v-container>
    <div class="svg-border-waves text-white">
      <v-img src="~@/assets/img/borderWavesBlue.svg"/>
    </div>
    <v-snackbar
        v-model="snackbar.enabled"
        timeout="3000"
        right
        top
        :color="snackbar.color"
    >
      {{ snackbar.text }}

      <template v-slot:action="{ attrs }">
        <v-btn
            text
            v-bind="attrs"
            @click="snackbar.enabled = false"
        >
          Fechar
        </v-btn>
      </template>
    </v-snackbar>
  </section>
</template>

<style scoped>
#contact {
  background-color: #f4f7f5;
}

.svg-border-waves .v-image {
  position: absolute;
  bottom: 0;
  left: 0;
  height: 3rem;
  width: 100%;
  overflow: hidden;
}

</style>

<script>
// import {db} from '@/main'

export default {
  data: () => ({
    icons: ["fa-facebook", "fa-twitter", "fa-linkedin", "fa-instagram"],
    valid: true,
    name: "",
    nameRules: [
      (v) => !!v || "O campo nome é obrigatório",
      (v) => (v && v.length >= 6) || "O nome precisa ter mais de 6 caracteres",
    ],
    email: "",
    emailRules: [
      (v) => !!v || "O campo email é obrigatório",
      (v) => /.+@.+\..+/.test(v) || "O E-mail precisa ser válido",
    ],
    textArea: "",
    textAreaRules: [
      (v) => !!v || "O campo de texto é obrigatório",
      (v) => (v && v.length >= 10) || "Mínimo de 10 caracteres",
    ],
    lazy: false,
    snackbar: {
      enabled: false,
      text: '',
      color: ''
    }
  }),
  methods: {
    submit() {
      /*db.collection("contactData").add({
        name: this.name,
        email: this.email,
        message: this.textArea
      }).then(() => {
        this.snackbar.text = "Mensagem enviada com sucesso"
        this.snackbar.color = "success"
        this.snackbar.enabled = true
      }).catch(() => {
        this.snackbar.text = "Erro ao enviar mensagem"
        this.snackbar.color = "danger"
        this.snackbar.enabled = true
      })*/
    }
  }
};
</script>
