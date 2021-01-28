<template>
  <div>
    <v-btn>
      <span>Linkedin</span>

      <v-icon>mdi-linkedin</v-icon>
    </v-btn>

    <v-btn>
      <span>Music</span>

      <v-icon>fa-github</v-icon>
    </v-btn>
  </div>
</template>

<script>
  export default {
    props: {
      large: {
        type: Boolean,
        default: false,
      },
    },

    data: () => ({
      items: [
        {
          name: 'Twitter',
          icon: 'fa-github',
        },
        {
          name: 'Instagram',
          icon: 'mdi-instagram',
        },
        {
          name: 'Facebook',
          icon: 'mdi-facebook',
        },
        {
          name: 'Email',
          icon: 'mdi-email',
        },
        {
          name: 'Phone',
          icon: 'mdi-phone',
        },
      ],
    }),
  }
</script>
