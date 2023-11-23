<script>
    export default {
        data() {
            return {
                navHeader: [
                    {
                        title: "CHARACTERS",
                        isActive: false,
                    },
                    {
                        title: "COMICS",
                        isActive: true,
                    },
                    {
                        title: "MOVIES",
                        isActive: false,
                    },
                    {
                        title: "TV",
                        isActive: false,
                    },
                    {
                        title: "GAMES",
                        isActive: false,
                    },
                    {
                        title: "COLLECTIBLES",
                        isActive: false,
                    },
                    {
                        title: "VIDEOS",
                        isActive: false,
                    },
                    {
                        title: "FANS",
                        isActive: false,
                    },
                    {
                        title: "NEWS",
                        isActive: false,
                    },
                    {
                        title: "SHOP",
                        isActive: false,
                    },
                ],
            };
        },
    };
</script>

<template>
    <div class="container">
        <div class="header">
            <img class="logo" src="../assets/img/dc-logo.png" alt="Logo DC">
            <ul>
                <li v-for="section in navHeader">
                    <a :class="{ active : section.isActive }" href="">{{ section.title }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
    .container{
        width: 80%;
        margin: auto;
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
                            color: #0c7cec;
                        }
                        &.active{
                            color: #0c7cec;
                        }
                    }
                }
            }
        };
    }
</style>