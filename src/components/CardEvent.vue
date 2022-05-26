<template>
    <div class="card text-center border-0 clear">
        <div class="card-header border-0 ">
            Featured
        </div>
        <div class="card-body border-0">
            <h5 class="card-title">Event</h5>
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum suscipit amet quo distinctio perspiciatis.    </p>
            <a href="#" class="link-info">Detail</a>
        </div>
        <div class="card-footer border-0">
            2 days ago
        </div>
    </div>
</template>

<script>
export default {
    name: "CardComponent"

}
</script>

<style scoped>
.card {
    width: 300px;
}
.clear {
    background: rgba(216, 216, 216, 0.5);
    box-shadow: 0 8px 10px 0 rgba(31, 38, 135, 0.37);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
}
</style>