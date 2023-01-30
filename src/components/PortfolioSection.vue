<template>
  <section id="portfolio" class="pb-8">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">



          <v-card style="width: 100%">
            <img height="150px" max-height="200px" src="~@/assets/img/BuffiVentures_headers_portfolio_sm.png"/>
            <v-divider class="my-6"></v-divider>
            <v-row class="text-center">
       
                        <!-- Build Networks -->
              <v-col class="col-12 col-sm-6 col-md-4">
                <div class="flex-center" min-height: 150px;>
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1a">
                        <div class="circle2">
                          <v-img src="~@/assets/img/build.white.logo.svg"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://www.buildcities.network/">Build_Republic</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">We build cities based on shared values, collective ownership, and human flourishing.</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/buildcities">                        
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>
                      </a></div>
                    <v-divider class="my-2"/>

                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.mdAndUp"></v-divider>
                </div>
                <v-divider class="mx-4" v-if="!this.$vuetify.breakpoint.smAndUp"></v-divider>
              </v-col>
              <!-- ETHTrust -->
              <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>

                <div class="flex-center" >
                  <v-card-text>
                    <div class="flex-center" >
                      <div class="circle1">
                        <div class="circle2">
                          <v-img src="~@/assets/img/ethtrust.logo.png"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://www.ethtrust.co/">ETHTrust</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Bringing Web3 to Banks and Credit unions</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/EthTrustCo">                        
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>
                      </a></div>
                    <v-divider class="my-2"/>
                  </v-card-text>
  
                </div>
                </v-col>

                <!-- Humna Finance -->
                <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1a">
                        <div class="circle2">
                          <v-img src="~@/assets/img/Huma_Vertical.png"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://huma.finance/">Huma Finance</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Income backed DeFi for the 99%.</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/humafinance">                        <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>
</a></div>
                    <v-divider class="my-2"/>

                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
  
                </div>

                </v-col>
                <!-- Social Stack -->
                <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle2">
                          <v-img src="~@/assets/img/socialstack.logo.jpeg"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://www.socialstack.co/">Social Stack</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Code-free social activations and campaigns </div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/trysocialstack/">                        <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>
</a></div>
                    <v-divider class="my-2"/>

                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
  
                </div>
              </v-col>
              <!-- Tavern Keeper -->
              <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle2">
                          <v-img src="~@/assets/img/TKTrimmed.logo.png"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://www.gmtavernkeeper.com/">Tavern Keeper</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Onboarding and community management</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/trysocialstack/">
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>
                    </a></div>
                    <v-divider class="my-2"/>

                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>

                </div>
              </v-col>
             
              <!-- Keyp -->
              <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle1">
                          <v-img src="~@/assets/img/keyp.logo.svg"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://usekeyp.com/">Keyp</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Onboarding Web2 communites to Web3 seamlessly</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">
                      <a href="https://twitter.com/usekeyp">
                        <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>
                      </a>
                    </div>
                    <v-divider class="my-2"/>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>

                </div>
               </v-col>
              </v-row>

<v-row class="text-center">
              <!-- Logos -->
              <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle2">
                          <v-img src="~@/assets/img/logos.logo.png"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://logos.xyz/">Logos</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Discover, connect, and thrive in the world of DAOs</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/0xlogos">
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>

                    </a></div>
                    <v-divider class="my-2"/>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
                </div>
              </v-col>
              <!-- VenturePunk -->
              <v-col class="col-12 col-md-4">
                <v-divider v-if="this.$vuetify.breakpoint.smOnly" class="mx-4"></v-divider>
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle2">
                          <v-img src="~@/assets/img/venture.punk.logo.jpeg"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://venturepunk.com/">VenturePunk</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Web3 Product Studio</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/venture_punk">
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>

                    </a></div>
                    <v-divider class="my-2"/>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
                </div>
              </v-col>

             <!-- Illust.space -->
              <v-col class="col-12 col-md-4">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1a">
                        <div class="circle2">
                          <v-img src="~@/assets/img/illust.agency.logo.png"/>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://www.illust.space/">Illust</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Engaging digital communities in physical space through maps, blockchain, and AR</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/IllustSpace">
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>

                    </a></div>
                    <v-divider class="my-2"/>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
                </div>
              </v-col>
         <!-- welook.io -->
         <v-col class="col-12 col-md-4">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle2">
                          <v-img src="~@/assets/img/welook.logo.jpeg"/>
                        </div> 
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://welook.io/">Welook</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Web3 Social platform, poaps, tickets, experience, IRL and Virtual</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/welook_io">
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>

                    </a></div>
                    <v-divider class="my-2"/>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
                </div>
              </v-col>
              <!-- Next -->
       <!-- NFTW -->
       <v-col class="col-12 col-md-4">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle1">
                          <v-img src="~@/assets/img/NFTW-Logo.jpg"></v-img>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2">
                      <a href="https://newfrontierworks.com/">New FronTier Works</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">Web3 Tokens, Fundraising, and engagement for IRL and Virtual Events</div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://twitter.com/works_frontier">
                      <i data-v-40ab164b="" aria-hidden="true" class="v-icon notranslate mdi mdi-twitter theme--light" style="font-size: 24px;"></i>

                    </a></div>
                    <v-divider class="my-2"/>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>                
                </div>
              </v-col>
                   <!-- Art Spark -->
                   <v-col class="col-12 col-sm-6 col-md-4">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
                      <div class="circle1">
                        <div class="circle2">
                          <v-img src="~@/assets/img/logo.artspark.svg"></v-img>
                        </div>
                      </div>
                    </div>
                    <div class="text--disabled text-uppercase text-h5 my-2"><a href="https://artspark.io">Art Spark</a></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text">AI Image Generation </div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"></div>
                    <v-divider class="my-2"/>
                    <div class="text-uppercase blue--text"><a href="https://discord.gg/artspark">Discord</a></div>
                    <v-divider class="my-2"/>
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.smAndUp"></v-divider>
                </div>
                <v-divider class="mx-4" v-if="!this.$vuetify.breakpoint.smAndUp"></v-divider>
              </v-col>
              <!-- Next -->

 
            </v-row>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <div class="svg-border-rounded text-light">
      <!-- <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 144.54 17.34"
        preserveAspectRatio="none"
        fill="currentColor"
      >
        <path
          d="M144.54,17.34H0V0H144.54ZM0,0S32.36,17.34,72.27,17.34,144.54,0,144.54,0"
        />
      </svg> -->
      <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 1440 320"
          preserveAspectRatio="none"
          fill="currentColor"
      >
        <path
            d="M0,64L80,90.7C160,117,320,171,480,181.3C640,192,800,160,960,138.7C1120,117,1280,107,1360,101.3L1440,96L1440,320L1360,320C1280,320,1120,320,960,320C800,320,640,320,480,320C320,320,160,320,80,320L0,320Z"
        ></path>
      </svg>
    </div>
  </section>
</template>

<style lang="scss">
$main_color: #283e79;

ul {
  font-size: 13px;
  line-height: 1.5em;
  margin: 5px 0 15px;
  padding: 0;

  li {
    list-style: none;
    position: relative;
    padding: 0 0 0 20px;
  }

  li {
    &::before {
      content: "";
      position: absolute;
      left: 0;
      top: 5px;
      width: 10px;
      height: 10px;
      background-color: $main_color;
      border-radius: 50%;
      -moz-border-radius: 50%;
      -webkit-eeborder-radius: 50%;
    }
  }
}
</style>

<style scoped>
.header {
  background-color: #283e79;
  color: white;
}

.circle1 {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  background-color: #f0f8ff;
  display: flex;
  align-items: center;
  justify-content: center;
}

.circle1a {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  background-color: #00060a;
  display: flex;
  align-items: center;
  justify-content: center;
}

.circle2 {
  border-radius: 50%;
  width: 100px;
  height: 100px;
  background-color: #00060a;
  display: flex;
  align-items: center;
  justify-content: center;
}

.flex-center {
  display: flex;
  align-items: center;
  justify-content: center;
}

.svg-border-rounded svg {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  color: #f4f7f5;
  z-index: -1;
}

#pricing {
  z-index: 0;
}

.content {
  z-index: 1;
}

svg {
  overflow: hidden;
}

section {
  position: relative;
}
</style>

<script>
export default {
  data: () => ({
    planos: [
      {
        title: "Básico",
        price: "R$100,00",
        img: "f1.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 3",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 4",
          },
        ],
      },
      {
        title: "Padrão",
        price: "R$150,00",
        img: "f2.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 3",
            color: "success",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 4",
          },
        ],
      },
      {
        title: "Premium",
        price: "R$250,00",
        img: "f3.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 3",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 4",
            color: "success",
          },
        ],
      },
    ],
  }),
  computed: {
    size() {
      const size = {md: "large", xl: "x-large"}[
          this.$vuetify.breakpoint.name
          ];
      return size ? {[size]: true} : {};
    }
  },
};
</script>