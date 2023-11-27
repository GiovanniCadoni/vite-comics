<script>
export default {

}
</script>

<template>
    <div class="container">
        <div class="content">
            <button>SIGN-UP NOW!</button>
            <ul>
                <li>FOLLOW US</li>
                <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                <li><img src="../assets/img/footer-periscope.png" alt=""></li>
                <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
                <li><img src="../assets/img/footer-twitter.png" alt=""></li>
                <li><img src="../assets/img/footer-youtube.png" alt=""></li>
            
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
.container {
    background-color: black;
    width: 100%;
    padding: 30px 0;

    .content {
        width: 80%;
        margin: auto;
        color: white;
        display: flex;
        justify-content: space-between;
        button{
            border-color: #0c7cec;
            background-color: black;
            color: white;
            padding: 10px 15px;
            font-weight: bolder;
        
        }
        ul{
            display: flex;
            gap: 10px;
            align-items: center;
            list-style: none;
            color: #0c7cec;
            font-weight: bold;
        }
    }
}
</style>