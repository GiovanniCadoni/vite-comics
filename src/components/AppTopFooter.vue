<script>
export default {

}
</script>

<template>
    <div class="container">
        <div class="content">
            <ul class="components">
                <li class="list">
                    <ul>
                        <li class="title">DC COMICS</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <ul>
                        <li class="title">SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC collectibles</li>
                    </ul>
                </li>
                <li class="list">
                    <ul>
                        <li class="title">DC</li>
                        <li>Terms of us</li>
                        <li>Privacy Policy</li>
                        <li>Ad choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscription</li>
                        <li>Talent Workshop</li>
                        <li>CPSC certificates</li>
                        <li>Ratings</li>
                        <li>Shop help</li>
                        <li>Contact us</li>
                    </ul>
                </li>
                <li class="list">
                    <ul>
                        <li class="title">SITES</li>
                        <li>DC</li>
                        <li>MAD magazine</li>
                        <li>DC kids</li>
                        <li>DC universe</li>
                        <li>DC power visa</li>
                    </ul>
                </li>
                
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container {
    width: 100%;
    background-image: url(../assets/img/footer-bg.jpg);
    padding: 30px 0;

    .content {
        width: 80%;
        margin: auto;
        color: white;

        .components {
            list-style: none;
            display: flex;
            gap: 50px;
        };
        .list {
            display: flex;
            flex-direction: column;
            font-size: 0.8rem;
            color: grey;
            gap: 20px;
            .title{
                font-weight: bolder;
                padding-bottom: 10px;
                font-size: 1.2rem;
                color: white;
            }
        }
        ul{
            list-style: none;
        }
    }
}</style>