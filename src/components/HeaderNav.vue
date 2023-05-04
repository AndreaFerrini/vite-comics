<script>

  export default{
    name: "HeaderNav",
    data(){
        return{
            menuLinks: [
                {
                    nome:`Characters`,
                    url: `https://www.dc.com/characters`,
                    current: false
                },
                {
                    nome:`Comics`,
                    url: `https://www.dc.com/comics`,
                    current: true
                },
                {
                    nome:`Movies`,
                    url: `https://www.dc.com/movies`,
                    current: false
                },
                {
                    nome:`TV`,
                    url: `https://www.dc.com/tv`,
                    current: false
                },
                {
                    nome:`Games`,
                    url: `https://www.dc.com/games`,
                    current: false
                },
                {
                    nome:`Collectibles`,
                    url: `https://www.dcuniverseinfinite.com/coming-soon/`,
                    current: false
                },
                {
                    nome:`Videos`,
                    url: `https://www.dc.com/videos`,
                    current: false
                },
                {
                    nome:`Fan`,
                    url: `https://www.dc.com/`,
                    current: false
                },
                {
                    nome:`News`,
                    url: `https://www.dc.com/news`,
                    current: false
                },
                {
                    nome:`Shop`,
                    url: `https://shop.dc.com/coming-soon/`,
                    current: false
                }
            ]
        }
    }
  }

</script>

<template>

<header class="container">
    <nav>
        <div class="d-flex justify-content-between py-3 align-items-center text-uppercase">
            <img src="public\img\dc-logo.png" alt="logo dc">
            <ul>
                <li v-for="(elem, index) in menuLinks" :key="index">
                    <a :class=" elem.current ? `active` : `` " :href="elem.url"> 
                        {{ elem.nome }}
                    </a>
                </li>

            </ul>
        </div>
    </nav>
</header>


</template>


<style scoped lang="scss">

header {
    height: 100px;
}

.container {
    width: 80%;
    max-width: 1280px;
    margin: 0 auto;
}

ul {
    list-style-type: none;
    display: flex;
    li{
        line-height: 100px;
    }
        a{
        display: flex;
        text-decoration: none;
        color: black;
        padding: 14px; 
        }
        :hover{
            border-bottom: 2px solid #0074e8;
        }
        :hover a {
            color: #0074e8;
        }
}
</style>