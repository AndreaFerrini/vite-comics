<script>

  import HeaderNav from "./components/HeaderNav.vue"
  import MainCard from "./components/MainCard.vue"
  import MainLinks from "./components/MainLinks.vue"

  export default{
    name: "App",
    components: {
      HeaderNav,
      MainCard,
      MainLinks,
    }
  }
</script>

<template>
  <div>
    <HeaderNav/>
    <MainCard/>
    <MainLinks/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;

</style>
