<script setup>
import FootPage from '../components/FootPage.vue';
import HeadPage from '../components/HeadPage.vue';
import Nav from '../components/Nav.vue';

</script>

<template>
  <HeadPage />
  <Nav></Nav>
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
