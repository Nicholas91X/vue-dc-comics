<template>
    <main>
        <h3> --> The content goes here  </h3>
    </main>
</template>

<script>
export default {
    name: "Main"
}
</script>

<style lang="scss">
    @import "../assets/style/partials/variables.scss";
    main {
        background-color: $secondary-color;
        height: 100px;
        display: flex;
        justify-content: flex-start;
        align-items: center;

        h3 {
        color: $tertiary-color;
        margin: 150px;
        }
    }
</style>