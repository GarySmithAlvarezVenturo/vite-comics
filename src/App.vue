<script>
import AHeader from "./components/AHeader.vue";
import AMain from "./components/AMain.vue";
import AFooter from "./components/AFooter.vue";

export default {
  components: {
    AHeader,
    AMain,
    AFooter,
  },
};
</script>

<template>
  <header>
    <AHeader />
  </header>

  <main>
    <AMain />
  </main>
  
  <footer>
    <AFooter />
  </footer>
  
</template>

<style lang="scss">
@use "./assets/styles/generals.scss" as *;



</style>
