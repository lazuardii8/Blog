<template>
  <section>
    <div class="container mx-auto">
      <div class="flex flex-wrap mb-10">
        <div class="w-1/2 my-auto">
          <div class="text-black-500 font-medium text-lg">Hallo, Saya Ardi</div>
          <div class="text-black-500 font-thin text-md">
            Saya adalah seorang freelancer website sejak tahun 2018.
          </div>
        </div>
        <div class="w-1/2 text-right my-auto">
          <p class="text-md font-thin">Front-developer</p>
          <p class="text-md font-thin">UiUX Enthusiast</p>
        </div>
      </div>

      <div class="flex flex-wrap mb-5">
        <div class="w-3/4">
          <h1 class="text-5xl font-bold leading-snug tracking-wide">
            Kami akan membantu dengan sebaik mungkin untuk menyelesaikan masalah
            anda.
          </h1>
        </div>
      </div>

      <div class="flex flex-wrap mb-10">
        <div class="w-1/2 font-thin text-6xl">
          01
        </div>
        <div class="w-1/2">
          <p class="leading-relaxed">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda,
            perferendis atque quaerat rerum, numquam laudantium cum sed
            obcaecati hic illum est, ratione cupiditate quasi consectetur
            incidunt eveniet enim nam et! Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Assumenda, perferendis atque quaerat
            rerum, numquam laudantium cum sed obcaecati hic illum est, ratione
            cupiditate quasi consectetur incidunt eveniet enim nam et!
          </p>
        </div>
      </div>

      <div class="paralax__image"></div>

      <h1 class="text-3xl font-bold leading-snug tracking-wide mb-5">
        Kami telah mengerjakan berbagai projek dasi sekala kecil hingga besar,
        untuk menambah kepercayaan kepada anda. anda dapat melihat beberaapa
        portofolio kami dibawah ini.
      </h1>

      <div class="grid grid-cols-3 gap-4">
        <CardPorto></CardPorto>
        <CardPorto></CardPorto>
        <CardPorto></CardPorto>
      </div>
    </div>
  </section>
</template>

<script>
import CardPorto from '~/components/CardPorto.vue'
export default {
  components: {
    CardPorto
  }
}
</script>

<style type="text/css" scoped="">
.container {
  max-width: 1200px;
}

section {
  padding: 80px 0;
}

.paralax__image {
  @apply mb-5;
  width: 100%;
  height: 450px;
  background-image: url('~@/assets/images/people-notes-meeting-team-7095 (1).jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
</style>
