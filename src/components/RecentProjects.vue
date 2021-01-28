<template>
  <v-container>
     <v-row>
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
                            :src="require('@/assets/otto.png')"
                            height="400px"
                            ></v-img>

                            <v-card-title>
                              Top western road trips
                            </v-card-title>

                            <v-card-subtitle>
                              1,000 miles of wonder
                            </v-card-subtitle>

                          <v-card-actions>
                              <v-btn
                                color="orange lighten-2"
                                text
                              >
                              Explore
                            </v-btn>

                          <v-spacer></v-spacer>

                          <v-btn
                       icon
                        @click="show = !show"
                        >
                      <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
                      </v-btn>
                    </v-card-actions>

                  <v-expand-transition>
                    <div v-show="show">
                      <v-divider></v-divider>

                      <v-card-text>
                        I'm a thing. But, like most
                        You won't have time for sleeping, soldier, not with all
                        the bed making you'll be doing. Then we'll go with that
                        data file! Hey, you add a one and two zeros to that or
                        we walk! You're going to do his laundry? I've got to
                        find a way to escape.
                        </v-card-text>
                        </div>
                  </v-expand-transition>
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
                  max-width="344"
                >
                      <v-img
                       :src="require('@/assets/project2.png')"
                        height="200px"
                      ></v-img>
                      <v-card-title>
                        Top western road trips
                      </v-card-title>
                      <v-card-subtitle>
                        1,000 miles of wonder
                      </v-card-subtitle>
                    <v-card-actions>
                        <v-btn
                          color="orange lighten-2"
                          text
                        >
                        Explore
                      </v-btn>
                    <v-spacer></v-spacer>
                    <v-btn
                  icon
                  @click="show = !show"
                  >
                  <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
                  </v-btn>
                </v-card-actions>
            <v-expand-transition>
              <div v-show="show">
                <v-divider></v-divider>
                <v-card-text>
                  I'm a thing. But, like most
                  politicians, he promised more than he could deliver. You won't hav
                </v-card-text>
              </div>
            </v-expand-transition>
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
                max-width="344"
              >
                      <v-img
                        :src="require('@/assets/rick.png')"
                        height="200px"
                      ></v-img>
                      <v-card-title>
                        Top western road trips
                      </v-card-title>
                      <v-card-subtitle>
                        1,000 miles of wonder
                      </v-card-subtitle>
                    <v-card-actions>
                        <v-btn
                          color="orange lighten-2"
                          text
                        >
                        Explore
                      </v-btn>
                    <v-spacer></v-spacer>
                    <v-btn
                  icon
                  @click="show = !show"
                  >
                  <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
                  </v-btn>
                </v-card-actions>
            <v-expand-transition>
              <div v-show="show">
                <v-divider></v-divider>
                <v-card-text>
                  I'm a thing. But, like most
                  politicians, he promised more than he could deliver. You won't hav
                </v-card-text>
              </div>
            </v-expand-transition>
          </v-card>
      </template>
      </v-col> <v-col
 cols="12"
 sm="6"
 md="6"
 >
   <template>
          <v-card
                class="mx-auto"
                max-width="344"
              >
                      <v-img
                      :src="require('@/assets/project31.png')"
                        height="200px"
                      ></v-img>
                      <v-card-title>
                        Top western road trips
                      </v-card-title>
                      <v-card-subtitle>
                        1,000 miles of wonder
                      </v-card-subtitle>
                    <v-card-actions>
                        <v-btn
                          color="orange lighten-2"
                          text
                        >
                        Explore
                      </v-btn>
                    <v-spacer></v-spacer>
                    <v-btn
                 icon
                  @click="show = !show"
                  >
                <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
                </v-btn>
              </v-card-actions>
            <v-expand-transition>
              <div v-show="show">
                <v-divider></v-divider>
                <v-card-text>
                  I'm a thing. But, like most
                  politicians, he promised more than he could deliver.
                  </v-card-text>
              </div>
            </v-expand-transition>
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
            max-width="1200PX"
          >
                <v-img
                :src="require('@/assets/project4.png')"
                height="600px"
                ></v-img>
                <v-card-title>
                  Top western road trips
                </v-card-title>
                <v-card-subtitle>
                  1,000 miles of wonder
                </v-card-subtitle>
              <v-card-actions>
                  <v-btn
                    color="orange lighten-2"
                    text
                  >
                  Explore
                </v-btn>
              <v-spacer></v-spacer>
              <v-btn
            icon
            @click="show = !show"
            >
            <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
            </v-btn>
          </v-card-actions>
      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            I'm a thing. But, like most
            politicians, he promised more than he could deliver. You won't hav
          </v-card-text>
        </div>
      </v-expand-transition>
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
