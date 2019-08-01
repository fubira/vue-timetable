<template>
  <v-app>
    <v-app-bar app>
      <v-spacer></v-spacer>
      <v-toolbar-title class="headline text-uppercase">
        <span class="font-weight-light headline">{{nowDate}}</span>
        <span class="font-weight-light display-2">{{nowTime}}</span>
      </v-toolbar-title>
    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import moment from 'moment';
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data: () => ({
    //
  }),
  computed: {
    nowDate: function() {
      return moment().format('YYYY/MM/DD');
    },
    nowTime: function() {
      return moment().format('HH:mm');
    }
  }
};
</script>
