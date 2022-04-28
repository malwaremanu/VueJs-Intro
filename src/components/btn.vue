<template>
  <div>
    <center>
      <button v-on:click="test" class="px-4 py-2 bg-green-600 text-white rounded-md">
        Button 2
      </button>
    </center>
  </div>
</template>

<script>
export default {
  name: "sample-button",
  methods: {
    test() {
      alert("this is another alert.");
    },
  },
};
</script>
