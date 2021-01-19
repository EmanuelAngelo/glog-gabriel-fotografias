<template>
  <base-card dark>
    <v-img
      :src="require('@/assets/articles/banner1.jpg')"
      class="grey lighten-2"
      height="600"
      width="100%"
    >
      <v-row
        class="fill-height pa-3"
        align="center"
      >
        <v-col
          cols="12"
          md="7"
          offset-md="5"
        >
          <h1 class="display-3 font-weight-light">
            Arte de Fotografar
          </h1>

          <div class="subheading text-uppercase pl-2 mb-4">
            Encontrando a beleza, uma foto de cada vez
          </div>

          <v-btn
            color="primary"
            depressed
            href="#subscribe"
          >
            Inscreva-se 
          </v-btn>
        </v-col>
      </v-row>
    </v-img>
  </base-card>
</template>

<script>
  export default {
    name: 'HomeBanner',
  }
</script>
