<template>
  <div>
    <h1>Geolocation</h1>
    <p>Your location is:</p>
    <p>
      Latitude: <span v-if="loc">{{ loc.coords.latitude }}</span>
    </p>
    <p>
      Longitude: <span v-if="loc">{{ loc.coords.longitude }}</span>
    </p>
    <v-btn block elevation="2" @click="getCurrentPosition">Get Current Location</v-btn>
    <v-btn block elevation="2" @click="scheduleNotification">Local Notifications</v-btn>
  </div>
</template>

<script>
import Vue from "vue";
export default Vue.extend({
  name: "Home",
  data: function() {
    return { loc: null };
  },
  methods: {
    getCurrentPosition: function() { },
    scheduleNotification: async function() { },
  }
});
</script>