<script>

  import HeaderNav from "./components/HeaderNav.vue"
  import MainCards from "./components/MainCards.vue"
  import MainLinks from "./components/MainLinks.vue"
  import MainGraphics from "./components/MainGraphics.vue"
  import FooterSocial from "./components/FooterSocial.vue"

  export default{
    name: "App",
    components: {
      HeaderNav,
      MainCards,
      MainLinks,
      MainGraphics,
      FooterSocial
    }
  }
</script>

<template>
  <div>
    <HeaderNav/>
    <MainCards/>
    <MainLinks/>
    <MainGraphics/>
    <FooterSocial/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;

</style>
