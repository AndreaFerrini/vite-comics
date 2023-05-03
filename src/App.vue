<script>

  import HeaderNav from "./components/HeaderNav.vue"

  export default{
    name: "App",
    components: {
      HeaderNav
    }
  }
</script>

<template>
  <div>
    <HeaderNav/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;

</style>
