<script>

export default{
  name: "FooterSocial",
}
</script>

<template>
    <footer>
        <div id="footer-social">
            <div class="container">
                <a href="" class="footer-sign-up text-uppercase">Sign up now!</a>
                <div class="footer-social-icon">
                    <span class="text-uppercase">Follow Us</span>
                    <ul class="d-flex">
                        <li>
                            <img src="/img/footer-facebook.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-periscope.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-pinterest.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-twitter.png" alt="">
                        </li>
                        <li>
                            <img src="/img/footer-youtube.png" alt="">
                        </li>
                    </ul>
                </div>
            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>

#footer-social{
    background-color: rgb(48,48,48);
    height: 125px;
    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        line-height: 75px;
        .footer-sign-up{
            color: white;
            text-decoration: none;
            border: 2px solid rgb(2,130,249);
            padding: 0 10px;
        }
        .footer-social-icon{
            display: flex;
            align-items: center;
            span{
                color: rgb(2,130,249);
            }
            ul{
                list-style: none;
                li{
                    padding: 10px;
                }
            }
        }    
    }   

}
</style>