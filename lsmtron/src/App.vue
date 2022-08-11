<template>
  <!-- App.vue -->
  <v-app>
    
    <HeaderLayout/>
    <NavigationLayout/>
    <!-- Sizes your content based upon application components -->
    <v-main>

      <!-- Provides the application the proper gutter -->
      <v-container fluid>

      </v-container>
    </v-main>

  </v-app>
</template>


<style lang="scss">
  @import './assets/scss/common.scss';
</style>

<script>
import HeaderLayout from './components/HeaderLayout';
import NavigationLayout from './components/NavigationLayout';
export default {
  name: 'App',

  components: {
    HeaderLayout,
    NavigationLayout,
  },
  data: () => ({
    //
  }),
};
</script>
