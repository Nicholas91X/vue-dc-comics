<template>
    <footer>
        <section id="first">
            <div class="container">
                <ul>
                    <li><img src="../assets/img/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</li>
                    <li><img src="../assets/img/buy-comics-merchandise.png" alt="">DC MERCHANDIZE</li>
                    <li><img src="../assets/img/buy-comics-shop-locator.png" alt="">SUBSCRIPTION</li>
                    <li><img src="../assets/img/buy-comics-subscriptions.png" alt="">COMIC SHOP LOCATOR</li>
                    <li><img src="../assets/img/buy-dc-power-visa.svg" alt="">DC POWER VISA</li>
                </ul>
            </div>
        </section>
        <section id="second">
            <div class="container">
                <div class="sub-container">
                    <div id="dc-comics-footer">
                        <h2>DC COMICS</h2>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                    <div id="shop-footer">
                        <h2>SHOP</h2>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                </div>
                <div class="sub-container">
                    <div id="dc-footer">
                        <h2>DC</h2>
                        <ul>
                            <li>Terms of use</li>
                            <li>Privacy policy (new)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Short Help</li>
                            <li>Contact us</li>
                        </ul>
                    </div>
                </div>
                <div class="sub-container">
                    <div id="sites-footer">
                        <h2>SITES</h2>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section id="third">
            <div class="container">
                <div id="sign-up"><button>Sign Up Now!</button></div>
                <div id="follow-us">
                    <div>
                        <h3>FOLLOW US</h3>
                        <ul>
                            <li><img src="../assets/img/footer-facebook.png" alt=""/></li>
                            <li><img src="../assets/img/footer-twitter.png" alt=""/></li>
                            <li><img src="../assets/img/footer-youtube.png" alt=""/></li>
                            <li><img src="../assets/img/footer-pinterest.png" alt=""/></li>
                            <li><img src="../assets/img/footer-periscope.png" alt=""/></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
    </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss">
    @import "../assets/style/partials/variables.scss";
    footer {
        ul {
            list-style: none;
        }

        #first {
            padding: 50px 0;
            background-color: $primary-color;
            
            ul {
                display: flex;
                justify-content: space-around;

                li {
                    display: flex;
                    align-items: center;
                    color: $tertiary-color;
                    margin-right: 50px;
                    text-transform: uppercase;
                    img {
                        width: 40%;
                        margin-right: 10px;
                    }
                }

                li:last-child {
                    width: 20%;
                }
            }
        }
        #second {
            background-image: url(../assets/img/footer-bg.jpg);
            padding: 30px;
            .container {
                justify-content: flex-start;
                align-items: flex-start;
                .sub-container {
                    margin-right: 35px;
                    h2 {
                        margin-bottom: 15px;
                    }
                    li {
                        margin-bottom: 3px;
                        color: lightgray;
                        font-size: 8px;
                    }
                    #shop-footer {
                        margin-top: 15px;
                    }
                }
            }
        }
        #third {
            background-color: rgba(48,48,48,255);
            padding: 20px;
            .container {
                #sign-up {
                    button {
                        padding: 5px 10px;
                        background-color: rgba(48,48,48,255);
                        color: $tertiary-color;
                        border-color: $primary-color;
                    }
                }
                #follow-us {
                    div {
                        display: flex;
                        justify-content: center;
                        align-items: center;
                        h3 {
                            color: $primary-color;
                        }
                        ul {
                            display: flex;
                            justify-content: center;
                            align-items: center;
                            li{
                                padding: 10px;
                            }
                        }
                    }
                }
            }
        }
    }
</style>