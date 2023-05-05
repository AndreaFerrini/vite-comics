<script>

import  AreaFumetti from "./AreaFumetti.vue"

export default{
  name: "MainCards",
  components: {
    AreaFumetti
  }
}

</script>

<template>
    <div id="area-fumetti">
        <div id="jumbotron">

        </div>
        <div class="container">
            <div id="blue-title">
                <h3>current series</h3>
            </div>
        </div>
        <AreaFumetti/>
    </div>
</template>

<style scoped lang="scss">

#area-fumetti{
    background-color: rgb(28,28,28);
    color: white;
    #jumbotron{
        background-image: url("/img/jumbotron.jpg");
        background-repeat: none;
        background-position: center;
        background-size: cover;
        min-height: 400px;
    }
    #blue-title{
        background-color: rgb(2,130,249);
        color: white;
        display: inline-block;
        padding: 15px;
        position: relative;
        top: -35px;
        }
    #container{
        margin: 0 auto;
        width: 80%;
        padding: 30px 0;
        h2{
            color: white;
        }
    }

}
</style>