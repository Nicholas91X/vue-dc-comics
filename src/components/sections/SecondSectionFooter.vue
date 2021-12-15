<template>
    <div>
        <div class="container">
            <div id="dc-comic-shop">
                <div>
                    <h3>DC Comics </h3>
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
                <div>
                    <h3>Shop</h3>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
            </div>
            
            <div id="dc-footer">
                <h3>DC</h3>
                <ul>
                    <li>Terms of use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact us</li>
                </ul>
            </div>
            <div id="sites">
                <h3>Sites</h3>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
            <img src="../../assets/img/dc-logo-bg.png" alt="">
        </div>
    </div>
</template>

<script>
export default {
    name: "SecondSectionFooter"
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    #dc-comic-shop,
    #dc-footer,
    #sites {
        margin: 10px;
        background-image: none;
    }
    #dc-comic-shop div:last-child h3 {
        margin-top: 10px;
    }
    div {
        background-image: url(../../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
        .container {
            background-image: none;
            display: flex;
            color: $tertiary-color;
            padding: 30px;
            overflow: hidden;
            h3 {
                font-size: 14px;
                text-transform: uppercase;
            }
            ul {
                list-style: none;
                li {
                    padding: 3px 0;
                    color: gray;
                }
            }
            img {
                width: 400px;
                position: absolute;
                top: -70px;
                right: 0;
            }
        }
    }
</style>