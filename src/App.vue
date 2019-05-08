<template>
  <v-app>
    <v-content>
      <Toolbar/>
    </v-content>
  </v-app>
</template>

<script>
import Toolbar from './components/Toolbar';

export default {
  name: 'App',
  components: {
    Toolbar,
  },
  data() {
    return {
      //
    };
  },
};
</script>
