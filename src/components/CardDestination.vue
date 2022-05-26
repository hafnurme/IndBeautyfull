<template>
    <div class="card text-white">
        <img :src="url" class="card-img" alt="...">
        <div class="card-img-overlay">
            <h5 class="card-title rounded-2 p-1 ">{{ title }}</h5>
        </div>
    </div>
</template>

<script>
export default {
    name: "CardDestination",
    props: {
        title: String
    },
    data() {
        return {
            url: this.title + ".webp"
        }
    }
}
</script>

<style scoped>
.card {
    width: 300px;
    height: 300px;
    overflow: hidden;
    display: flex;
}

img {
    position: absolute;
    top: 0;
}

.card-title {
    background: rgba(59, 59, 59, 0.2);
    width: fit-content;
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
}
</style>