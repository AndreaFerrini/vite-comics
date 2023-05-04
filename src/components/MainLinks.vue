<script>

export default{
  name: "MainLinks",
    data(){
        return{
            icons: [
                {
                    nome: `digital Comic`,
                    path: `buy-comics-digital-comics.png`
                },
                {
                    nome: `dc merchandise`,
                    path: `buy-comics-merchandise.png`
                },
                {
                    nome: `subscriptions`,
                    path: `buy-comics-subscriptions.png`
                },
                {
                    nome: `comic shop locator`,
                    path: `buy-comics-shop-locator.png`
                },
                {
                    nome: `dc power visa`,
                    path: `buy-dc-power-visa.svg`
                }
            ]
        }
    }
}

</script>

<template>
    <div class="Links">
        <div class="container py-5 text-uppercase">
            <ul class="d-flex justify-content-between align-items-center">
                <li v-for="(elem, index) in icons" :key="index">
                    <img :src="`/img/${elem.path}`" alt="nome icona">
                    <span class="icon-text">{{ elem.nome }}</span>
                </li>
            </ul>
        </div>
    </div>  
</template>

<style lang="scss" scoped>
.Links {
    background-color: rgb(2,130,249);
    padding: 5px 0;
    .container{
        margin: 0 auto;
        width: 80%;
        ul{
            li{
                display: flex;
                align-items: center;
                list-style: none;
                img{
                    height: 70px;
                    margin-right: 10px;
                }
                span{
                    color: white;
                }
            }
        }
    }
}

</style>