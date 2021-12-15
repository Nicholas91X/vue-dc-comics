<template>
    <button>
        Sign Up Now
    </button>
</template>

<script>
export default {
    name: "ButtonSign"
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    button {
        padding: 5px 12px;
        border: 1px solid $primary-color;
        background-color: #303030;
        color: $tertiary-color;
        text-transform: uppercase;
    }
</style>