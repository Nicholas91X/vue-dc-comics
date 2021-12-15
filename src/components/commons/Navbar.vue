<template>
    <div>
        <ul>
            <li v-for="(link,index) in links" :class="{active : link.current}" :key="index"><a :href="link.url">{{link.text}}</a></li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "Navbar",
    data() {
        return {
            links: [
                {
                    text: "Characters",
                    url: "#",
                    current: false
                },
                {
                    text: "Comics",
                    url: "#",
                    current: false
                },
                {
                    text: "Movies",
                    url: "#",
                    current: false
                },
                {
                    text: "TV",
                    url: "#",
                    current: false
                },
                {
                    text: "Games",
                    url: "#",
                    current: false
                },
                {
                    text: "Collectibles",
                    url: "#",
                    current: false
                },
                {
                    text: "Video",
                    url: "#",
                    current: false
                },
                {
                    text: "Fans",
                    url: "#",
                    current: false
                },
                {
                    text: "News",
                    url: "#",
                    current: false
                },
                {
                    text: "Shop",
                    url: "#",
                    current: false
                }
            ]
        }
        
    }
}
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
@import "../../assets/style/global.scss";
    ul {
        list-style: none;
        display: flex;
        li {
            height: 100px;
            padding: 10px;
            text-transform: uppercase;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            &.active, &:hover {
                    border-bottom: 5px solid $primary-color;
                    color: $primary-color;
                }
            a {
                text-decoration: none;
                color: $secondary-color;
                &:hover {
                    color: $primary-color;
                }
            }
        }
    }
</style>