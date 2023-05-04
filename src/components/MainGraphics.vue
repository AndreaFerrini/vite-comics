<script>

export default{
  name: "MainGraphics",

}
</script>

<template>
    <div class="copertina">
        <div class="container">
            <div class="col-1 d-flex">
                <div id="menu-1">
                    <h4>dc comics</h4>
                    <ul>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Movies</a>
                        </li>
                        <li>
                            <a href="#">TV</a>
                        </li>
                        <li>
                            <a href="#">Games</a>
                        </li>
                        <li>
                            <a href="#">Videos</a>
                        </li>
                        <li>
                            <a href="#">News</a>
                        </li>
                    </ul>
                    <h4>shop</h4>
                    <ul>
                        <li>
                            <a href="#">Shop DC</a>
                        </li>
                        <li>
                            <a href="#">Shop DC Collectibles</a>
                        </li>
                    </ul>
                </div>
                <div id="menu-1">
                    <h4>dc</h4>
                    <ul>
                        <li>
                            <a href="#">Terms of Use</a>
                        </li>
                        <li>
                            <a href="#">Privacy policy (New)</a>
                        </li>
                        <li>
                            <a href="#">Ad Choices</a>
                        </li>
                        <li>
                            <a href="#">Advertising</a>
                        </li>
                        <li>
                            <a href="#">Jobs</a>
                        </li>
                        <li>
                            <a href="#">Subscriptions</a>
                        </li>
                        <li>
                            <a href="#">Talent Workshop</a>
                        </li>
                        <li>
                            <a href="#">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="#">Ratings</a>
                        </li>
                        <li>
                            <a href="#">Shop Help</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                    </ul>
                </div>
                <div id="menu-1">
                    <h4>sites</h4>
                    <ul>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="#">DC Kids</a>
                        </li>
                        <li>
                            <a href="#">DC Universe</a>
                        </li>
                        <li>
                            <a href="#">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped lang="scss">

.copertina {
    background-image: url( "/img/footer-bg.jpg" );
    color: white;
    height: 400px;

    .container{
        background-image: url( "/img/dc-logo-bg.png" );
        background-repeat: no-repeat;
        background-size: 35%;
        background-position: center right;
        padding: 30px 0;
        div{
            width: 50%;
            h4{
                text-transform: uppercase;
                margin-bottom: 15px;
            }
            ul{
                padding: 0;
                li{
                    list-style: none;
                    line-height: 180%;
                    a{
                        text-decoration: none;
                        color: rgb(149,149,149);
                    }
                }
            }
            div{
                width: calc( 100% / 3 );
            }
        }

    }
}
</style>