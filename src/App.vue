<script>

  import HeaderNav from "./components/HeaderNav.vue"
  import MainCard from './components/MainCard.vue'

  export default{
    name: "App",
    components: {
      HeaderNav,
      MainCard,
    }
  }
</script>

<template>
  <div>
    <HeaderNav/>
    <MainCard/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;

</style>
