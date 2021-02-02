<template>
  <v-container>
    <v-row no-gutters>
      <v-col
        class="primary text-center pa-5 white--text"
        cols="12"
        md="12"
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateX(25%)"
        />

        <base-heading>
          Proyectos Recientes
        </base-heading>

        <base-text class="mb-5 mt-5">
          Este portafolio está diseñado con Vuetify. <v-icon>fa-pencil</v-icon>
        </base-text>
       </v-col>
    </v-row>
      <v-row class="primary">
      <v-col
          class='primary'
          cols="12"
          sm="6"
          md="6"
       >
         <template>
                <v-card
                      class="mx-auto"
                      max-width="600"
                >
                            <v-img
                            :src="require('@/assets/krauss.png')"
                            height="400px"
                            aspect-ratio="1.7"
                            contain
                            ></v-img>

                            <v-card-title>
                              Tienda de juguetes
                            </v-card-title>

                            <v-card-subtitle>
                              Realizada con Bootstrap-vue la página está conectada a una base de datos en Firebase. Incluye control de acceso.
                            </v-card-subtitle>
                </v-card>
         </template>
      </v-col>
       <v-col
          cols="12"
          sm="6"
          md="6"
          >
        <template>
              <v-card
                  class="mx-auto"
                  max-width="600"
                >
                      <v-img
                       :src="require('@/assets/project2.png')"
                        height="400px"
                        aspect-ratio="1.7"
                        contain
                      ></v-img>
                      <v-card-title>
                         Trekking
                      </v-card-title>
                      <v-card-subtitle>
                        Sitio realizado en  CSS.
                        <br>
                        <br>
                      </v-card-subtitle>
              </v-card>
          </template>
        </v-col>
       <v-col
         cols="12"
         sm="6"
         md="6"
      >
      <template>
        <v-card
                class="mx-auto"
                max-width="600"
              >
                      <v-img
                          :src="require('@/assets/rick.png')"
                          height="400px"
                          aspect-ratio="1.7"
                          contain
                      ></v-img>
                      <v-card-title>
                        Rick and Morty
                      </v-card-title>
                      <v-card-subtitle>
                        La página está conectada a Api y basada en Bootstrap.
                      </v-card-subtitle>
              </v-card>
        </template>
      </v-col>
       <v-col
         cols="12"
         sm="6"
         md="6"
       >
        <template>
          <v-card
                class="mx-auto"
                max-width="600"
          >
                      <v-img
                      :src="require('@/assets/project31.png')"
                        height="400px"
                        aspect-ratio="1.7"
                        contain
                      ></v-img>
                      <v-card-title>
                        Conferencias en un café
                      </v-card-title>
                      <v-card-subtitle>
                        Integramente realizada en CSS
                      </v-card-subtitle>
             </v-card>
          </template>
        </v-col>
        <v-col
              cols="12"
              sm="12"
              md="12"
        >
         <template>
           <v-card
                class="mx-auto"
                max-width="500"
            >
                        <v-img
                        :src="require('@/assets/project4.png')"
                        height="400px"
                        aspect-ratio="1.7"
                        contain
                        ></v-img>
                        <v-card-title>
                        Revista de Autos
                    </v-card-title>
                       <v-card-subtitle>
                          Realizada usando CSS y Bootstrap.
                      </v-card-subtitle>
                </v-card>
            </template>
          </v-col>
      </v-row>
  </v-container>
</template>
<script>
  export default {
    name: 'RecentProjects',
    data: () => ({
      show: false,
    }),
  }
</script>
