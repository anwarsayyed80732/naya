<template>
  <v-app>
    <v-app-bar app color="black" dark>
      <div class="d-flex align-center">
        <v-toolbar-title>Tod App</v-toolbar-title>
      </div>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
