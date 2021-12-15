<template>
    <section id="first">
        <div class="container">
            <div class="box">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <h3>Digital Comics</h3>
            </div>
            <div class="box">
                <img src="../../assets/img/buy-comics-merchandise.png" alt="">
                <h3>DC Merchandise</h3>
            </div>
            <div class="box">
                <img src="../../assets/img/buy-comics-shop-locator.png" alt="">
                <h3>Subscription</h3>
            </div>
            <div class="box">
                <img src="../../assets/img/buy-comics-subscriptions.png" alt="">
                <h3>Comic Shop Locator</h3>
            </div>
            <div class="box">
                <img src="../../assets/img/buy-dc-power-visa.svg" alt="">
                <h3>DC Power Visa</h3>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "FirstSectionFooter"
}

</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    #first {
        width: 100%;
        background-color: $primary-color;
        padding: 30px 0;
        .container {
            display: flex;
            justify-content: space-evenly;
            align-items: center;
        }
        .box {
            display: flex;
            align-items: center;
            img {
                width: 50px;
            };
            h3 {
                color: $tertiary-color;
                text-transform: uppercase;
                margin-left: 10px;
            }
        }
    }
</style>