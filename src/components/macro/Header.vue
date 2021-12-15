<template>
    <div>
        <div class="container">
            <Logo/>
            <Navbar/>
        </div>
            <Hero/>
    </div>
</template>

<script>
import Logo from "../commons/Logo.vue";
import Navbar from "../commons/Navbar.vue";
import Hero from "../commons/Hero.vue";
export default {
    name: "Header",
    components:
     {
        Logo,
        Navbar,
        Hero
    }
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    div.container {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
</style>