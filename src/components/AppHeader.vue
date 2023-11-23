<script>
    export default {
        data() {
            return {
                navHeader: [
                    {
                        title: "CHARACTERS"
                    },
                    {
                        title: "COMICS"
                    },
                    {
                        title: "MOVIES"
                    },
                    {
                        title: "TV"
                    },
                    {
                        title: "GAMES"
                    },
                    {
                        title: "COLLECTIBLES"
                    },
                    {
                        title: "VIDEOS"
                    },
                    {
                        title: "FANS"
                    },
                    {
                        title: "NEWS"
                    },
                    {
                        title: "SHOP"
                    },
                ],
            };
        },
    };
</script>

<template>
    <div class="header">
        <img class="logo" src="../assets/img/dc-logo.png" alt="Logo DC">
        <ul>
            <li v-for="section in navHeader"><a href="">{{ section.title }}</a></li>
        </ul>
    </div>
</template>

<style scoped lang="scss">
    .header{
        height: 100px;
        padding: 80px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
        ul{
            display: flex;
            gap: 20px;
            li{
                list-style: none;
                a{
                    text-decoration: none;
                    color: black;
                    font-weight: bolder;
                    &:hover{
                        color: blue;
                    }
                }
            }
        }
    };
</style>