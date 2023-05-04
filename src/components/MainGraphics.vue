<script>

export default{
  name: "MainGraphics",

}
</script>

<template>
    <div class="copertina">
        <div class="container">
            <ul>
                <li>dc comics</li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
            </ul>
        </div>
    </div>




</template>

<style scoped lang="scss">

.copertina {
    background-image: url( `src/assets/img/footer-bg.jpg` );
    color: white;
    .container{
        background-image: url( `src/assets/img/dc-logo-bg.png` );
        background-repeat: no-repeat;
        background-size: 40%;
        background-position: center right;
    }
}

</style>