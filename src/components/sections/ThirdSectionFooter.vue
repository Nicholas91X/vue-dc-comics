<template>
    <div>
        <div class="container">
            <ButtonSign/>
            <div id="follow-us">
                <h3>Follow Us</h3>
                <ul>
                    <li><img src="../../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../../assets/img/footer-twitter.png" alt=""></li>
                    <li><img src="../../assets/img/footer-youtube.png" alt=""></li>
                    <li><img src="../../assets/img/footer-pinterest.png" alt=""></li>
                    <li><img src="../../assets/img/footer-periscope.png" alt=""></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
import ButtonSign from "../commons/ButtonSign.vue"
export default {
    name: "ThirdSectionFooter",
    components: {
        ButtonSign
    }
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    div {
        background-color: #303030;
        .container {
            display: flex;
            justify-content: space-between;
            position: relative;
            padding: 20px;
            #sign-up {
                border: 1px solid $primary-color;
                padding: 5px 12px;
            }
            #follow-us {
                display: flex;
                align-items: center;
                h3 {
                    color: $primary-color;
                    text-transform: uppercase;
                    margin-right: 10px;
                }
                ul {
                    list-style: none;
                    display: flex;
                    li {
                        padding: 5px;
                    }
                }
            }
        }
    }
</style>