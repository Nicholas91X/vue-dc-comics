<template>
    <header>
        <div class="container">
            <div id="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo">
            </div>
            <nav>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>

export default {
    name: "Header"
}
</script>

<style lang="scss">
@import "../assets/style/partials/variables.scss";
    header {
        margin: 20px 0;
    }
    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;

        nav ul {
            display: flex;
            list-style: none;

            li a {
                padding: 62px 10px;
                text-transform: uppercase;
                text-decoration: none;
                color: $secondary-color;

                &:hover {
                    border-bottom: 5px solid $primary-color;
                }
            }
        }
    }
</style>