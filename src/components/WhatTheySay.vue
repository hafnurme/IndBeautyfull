<template>
  <div class="card m-3">
      <div class="card-body">
          <h4>{{ destination }}</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae vero deleniti optio error earum molestias ullam illo porro, dolores amet tempora blanditiis, officia aperiam harum inventore id quas dolorem quam.</p>
          <div class="mt-4 d-flex align-items-center">
              <div class="rounded-circle bg-dark round me-3"></div>
              <h5>{{ name }}</h5>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "WhatTheySay",
    props: {
        name: String,
        destination: String,
    }
}
</script>

<style scoped>
    .card {
        width: 300px;
    }
    .round {
        width: 40px;
        height: 40px;
    }
</style>