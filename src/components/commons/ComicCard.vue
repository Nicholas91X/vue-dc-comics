<template>
    <div class="card">
        <div id="card-img">
            <img :src="comic.thumb" :alt="comic.series">
        </div>
        <h3>{{comic.series}}</h3>
        
    </div>
</template>

<script>
export default {
    name: "ComicCard",
    props: {
        comic: Object
    }
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    .card {
        margin: 15px;
        display: flex;
        flex-direction: column;
        #card-img {
            img {
                width: 100%;
            }
        }
        h3 {
            background-color: $secondary-color;
            color: lightgray;
            text-transform: uppercase;
        }
    }
</style>