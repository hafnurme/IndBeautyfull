<template>
    <div class="card my-5 border-0 px-5 py-2">
        <div class="card-body">
            <h2 class="my-4">Want to stay updated about Indonesia?</h2>
            <p>Email updates every week!</p>
            <input type="email" class="form-control my-3 border-0 p-2 px-4" id="exampleFormControlInput1" placeholder="youremail@example.com">
            <button class="btn btn-light mb-4">Suscribe Now</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BerlanggananComponent'
}
</script>

<style scoped>
.card {
    background: linear-gradient(90deg, rgba(0, 200, 255, 0.3) 0%, rgba(146, 254, 157, 0.3) 100%);
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
}
</style>