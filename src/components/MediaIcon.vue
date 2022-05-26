<template>
  <div class="container p-3 d-flex flex-wrap">
      <div class="rounded-circle a m-1"></div>
      <div class="rounded-circle b m-1"></div>
      <div class="rounded-circle c m-1"></div>
      <div class="rounded-circle d m-1"></div>
  </div>
</template>

<script>
export default {
    name: "MediaIcon"

}
</script>

<style scoped> 

    .container {
        height: 100px;
        justify-content: center;
    }
    .container div {
        width: 50px;
        height: 50px;
    }
    .a {
        background-color: rgb(99, 99, 240);
    }
    .b {
        background-color: rgb(248, 82, 179);
    }
    .c {
        background-color: rgb(127, 197, 255);
    }
    .d {
        background-color: rgb(123, 209, 36);
    }
</style>