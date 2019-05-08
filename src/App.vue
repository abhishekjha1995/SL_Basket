<template>
  <v-app>
    <v-content>
        <Toolbar/>
        <Offers/>
    </v-content>
  </v-app>
</template>

<script>
import Toolbar from './components/Toolbar';
import Offers from './components/Offers';

export default {
  name: 'App',
  components: {
    Toolbar,
    Offers,
  },
  data() {
    return {
      //
    };
  },
};
</script>
