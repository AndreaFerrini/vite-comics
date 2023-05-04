<script>

  import HeaderNav from "./components/HeaderNav.vue"
  import MainCards from "./components/MainCards.vue"
  import MainLinks from "./components/MainLinks.vue"

  export default{
    name: "App",
    components: {
      HeaderNav,
      MainCards,
      MainLinks,
    }
  }
</script>

<template>
  <div>
    <HeaderNav/>
    <MainCards/>
    <MainLinks/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;

</style>
