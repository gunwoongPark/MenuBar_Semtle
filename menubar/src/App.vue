<template>
  <v-app>
    <v-main>
      <v-container style="height:10000px">
        <main-menu-bar id="mainmenubar" />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import MainMenuBar from "./components/MainMenuBar.vue";
export default {
  components: {
    MainMenuBar,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
#mainmenubar {
  position: sticky;
  top: 20px;
}
</style>
