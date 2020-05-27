<template>
  <div class="bg-white p-3 rounded-md card__grub">
    <div class="image__card">
      <img
        src="~/assets/images/people-notes-meeting-team-7095 (1).jpg"
        alt=""
        class=""
      />
    </div>
    <div class="block text-xl font-bold">Simpangh Project</div>
    <div class="block text-md font-thin">12 April 2020</div>
  </div>
</template>

<script>
export default {
  name: 'CardPorto',

  data() {
    return {}
  }
}
</script>

<style lang="css" scoped>
.image__card {
  @apply rounded-md mb-3;
  width: 100%;
  height: 250px;
  overflow: hidden;
}

.image__card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: 0.5s;
}
.card__grub:hover .image__card img {
  transform: scale(1.1);
}
</style>
