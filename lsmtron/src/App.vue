<template>
  <!-- App.vue -->
  <v-app>
    
    
    <HeaderLayout/>
    <NavigationLayout/>
    <!-- Sizes your content based upon application components -->
    <v-main>

      <!-- Provides the application the proper gutter -->
      <v-container fluid>

        <!-- If using vue-router -->
        <router-view></router-view>
      </v-container>
    </v-main>

  </v-app>
</template>

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
