<template>
  <div id="appform">
    <appscorecard v-if="step == 1" />
  </div>
</template>

<script>
  import appscorecard from "./formsections/AppScorecard.vue";

  export default {
    name: "AppForm1",
    components: {
      appscorecard,
    },
    data() {
      return {
        step: 1,
      };
    },
    methods: {
      updatestep() {
        this.step = this.step + 1;
      },
    },
  };
</script>

<style>
  #appform {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    flex-direction: column;
  }

  input,
  select {
  }

  button {
  }
</style>
