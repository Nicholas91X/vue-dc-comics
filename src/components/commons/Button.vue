<template>
    <button>Load More</button>
</template>

<script>
export default {
    name: "Button"
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    button {
        padding: 5px 18px;
        position: absolute;
        bottom: 10px;
        left: 50%;
        transform: translateX(-50%);
        text-transform: uppercase;
        background-color: $primary-color;
        color: $tertiary-color;
        border-style: none;
    }
</style>