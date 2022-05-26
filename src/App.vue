<template>
  <nav class="navbar navbar-light navbar-expand-lg position-fixed top-0 w-100">
    <div class="container">
      <a class="navbar-brand fs-6" href="/">BeautifulIndonesia
        <p class="m-0 moto">Explore The Beautiful of Indonesia</p>
      </a>
      <div class="collapse navbar-collapse" id="navbarNav">
      </div>
    </div>
  </nav>
  <router-view />
  <footer class="container-fluid bg-dark py-4 px-5   text-white">
    <h2 class="mb-4 text-center">Thank You for Visiting!</h2>
    <div class="d-flex container flex-wrap">
      <img src="./assets/img/DiIndonesiaAja.webp" alt="diindinesiaaja" class="diindo my-2 me-5">
      <div class="text-white">
        <p class="">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Autem, quibusdam adipisci. Eaque sequi
          tenetur
          debitis ad, asperiores ullam quo quod, minus accusamus quos doloremque harum excepturi. Sed cumque ab nulla.
        </p>
        <p>Lorem</p>
      </div>
    </div>
  </footer>
  <p class="text-white text-center mb-0 cop py-2">Copyright 2022. Hafid Nur Kholis </p>
</template>

<script>

export default {
  created() {
    document.title = "Beautiful Indonesia"
  }
}

</script>

<style scoped>
.navbar {
  background: rgba(255, 255, 255, 0.8);
  box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
  backdrop-filter: blur(5px);
  -webkit-backdrop-filter: blur(5px);
  z-index: 199;
}

body {
  background-color: black;
  padding: 0;
  margin: 0;
}

footer {
  margin-top: 100px;
}

.moto {
  font-size: 12px;
}

.diindo {
  border-radius: 30px;
  height: 160px;
}

.cop {
  background-color: black;
}
</style>
