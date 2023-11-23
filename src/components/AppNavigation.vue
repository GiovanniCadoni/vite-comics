<script>
    export default {
        data () {
            return {
                navigationMenu: [
                    {
                        img: "img/buy-comics-digital-comics.png",
                        title: "DIGITAL COMICS",
                    },
                    {
                        img: "img/buy-comics-merchandise.png",
                        title: "DC MERCHANDISE",
                    },
                    {
                        img: "img/buy-comics-subscriptions.png",
                        title: "SUBSCRIPTION",
                    },
                    {
                        img: "img/buy-comics-shop-locator.png",
                        title: "COMIC SHOP LOCATOR",
                    },
                    {
                        img: "img/buy-dc-power-visa.svg",
                        title: "DC POWER VISA",
                    },
                ],
            };
        },
        methods: {
            getImagePath: function(img) {
                return new URL (`../assets/${img}`, import.meta.url).href;
            }
        }
    };
</script>

<template>
    <div class="container">
        
        <section class="navigation">
            <ul>
                <li v-for="section in navigationMenu">
                    <img :src="getImagePath(section.img)" alt="">
                    <a href="">{{ section.title }}</a>
                </li>
            </ul>
        </section>
    </div>
</template>

<style scoped lang="scss">
    .container{
        background-color: #0c7cec;
        .navigation{
            width: 80%;
            margin: auto;
            color: white;
            padding: 30px 0;
            ul{
                display: flex;
                justify-content: space-around;
                li{
                    display: flex;
                    align-items: center;
                    gap: 8px;
                    list-style: none;
                    img{
                        height: 75px;
                    }
                    a{
                        text-decoration: none;
                        color: white;
                        font-size: .8rem;
                        &:hover{
                            text-decoration: underline;
                            color: black
                        }
                    }
                }
            }
        }
    }
</style>