<template>
  <CarouselVue />
  <hr>
  <MediaIconVue />
  <hr>
  <div class="container">
    <div class="container-fluid  py-5">
      <h1 class="text-center mb-2">Event Held</h1>
      <div class="container d-flex justify-content-around p-4 flex-wrap">
        <CardEvent class="m-3" />
        <CardEvent class="m-3" />
        <CardEvent class="m-3" />
      </div>
    </div>
    <hr>
    <div class="container text-center my-5">
      <h1>#DiIndonesiaAja</h1>
      <p class="fs-4">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Odio obcaecati nihil quas facilis error
        maiores cum
        minus commodi quaerat nam, eveniet distinctio harum rerum architecto qui, quod, explicabo quo ipsa!</p>
    </div>
    <div class="container p-4 my-5 d-flex flex-wrap justify-content-center">
      <CardDestination title="Bali" class="m-4" />
      <CardDestination title="Lombok" class="m-4" />
      <CardDestination title="Yogyakarta" class="m-4" />
      <CardDestination title="Bandung" class="m-4" />
      <CardDestination title="Jakarta" class="m-4" />
    </div>
    <hr>
    <div class="container my-5">
      <h1 class="text-center my-5">What They Say ?</h1>
      <div class="container d-flex flex-wrap justify-content-center">
        <WhatTheySay name="Anna Mira" destination="Labuan Bajo" />
        <WhatTheySay name="Anderson Reinar" destination="Raja Ampat" />
        <WhatTheySay name="Sujiwo Eko" destination="Borobudur" />
      </div>
    </div>
    <hr>
    <BerlangganVue />
  </div>
</template>

<script>
// @ is an alias to /src
import CarouselVue from '@/components/Carousel.vue'
import CardEvent from '@/components/CardEvent.vue'
import CardDestination from '@/components/CardDestination.vue'
import MediaIconVue from '@/components/MediaIcon.vue'
import WhatTheySay from '../components/WhatTheySay.vue'
import BerlangganVue from '@/components/Berlanggan.vue'

export default {
  name: 'HomeView',
  components: {
    CarouselVue,
    CardEvent,
    CardDestination,
    MediaIconVue,
    WhatTheySay,
    BerlangganVue
  }
}
</script>

<style scoped>
</style>