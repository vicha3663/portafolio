<template>
  <section
    id="get-in-touch"
    class="overflow-hidden"
  >
    <v-row
      class="info white--text"
      no-gutters
    >
      <v-col
        class="hidden-sm-and-down"
        md="6"
      >
        <v-img
          :src="require('@/assets/contactus.png')"
          height="100%"
        />
      </v-col>
      <v-col
        class="pa-5"
        cols="12"
        md="6"
      >
        <base-bubble-1 />

        <base-heading class="mb-5">
          Escríbeme
        </base-heading>

        <v-sheet
          color="transparent"
          max-width="600"
        >
          <v-text-field
            color="info"
            label="Nombre"
            solo
            flat
          />

          <v-text-field
            color="info"
            label="Correo electrónico"
            solo
            flat
          />

          <v-text-field
            color="info"
            label="Tema"
            solo
            flat
          />

          <v-textarea
            color="info"
            label="Mensaje"
            solo
            flat
          />

          <base-btn>Enviar</base-btn>
        </v-sheet>
      </v-col>
    </v-row>
  </section>
</template>

<script>
  export default {
    name: 'GetInTouch',
  }
</script>
