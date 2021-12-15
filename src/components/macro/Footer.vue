<template>
    <div>
        <First-section-footer/>
        <Second-section-footer/>
        <Third-section-footer/>
    </div>
</template>

<script>
import FirstSectionFooter from "../sections/FirstSectionFooter.vue";
import SecondSectionFooter from "../sections/SecondSectionFooter.vue";
import ThirdSectionFooter from "../sections/ThirdSectionFooter.vue";
export default {
    name: "Footer",
    components: {
        FirstSectionFooter,
        SecondSectionFooter,
        ThirdSectionFooter
    }
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    
</style>