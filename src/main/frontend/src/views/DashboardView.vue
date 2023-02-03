<script setup>
import FootPage from '../components/FootPage.vue';
import HeadPage from '../components/HeadPage.vue';
import ListAnimals from '../components/ListAnimals.vue';
</script>

<template>
  <HeadPage />
  <main>
  <ListAnimals />
  </main>
  <FootPage />
</template>

<style lang="scss" scoped>
main{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 80vh;
}

</style>
