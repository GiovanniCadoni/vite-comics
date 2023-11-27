<script>
export default {
    props: {
        image: String,
        title: String,
    },
};
</script>

<template>
    <div class="card">
        <img :src="image" alt="">
        <p>{{ title }}</p>
    </div>

</template>

<style scoped lang="scss">
.card{
    padding: 0 10px;
    img{
        width: 100%;
        aspect-ratio: 1;
        object-fit: cover;
    }
    p{
        padding-top: 10px;
        font-weight: bold;
    }
}
</style>