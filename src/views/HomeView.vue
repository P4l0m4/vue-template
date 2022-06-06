<template>
  <div class="home">
    <h1 class="home__title">
      {{ msg }}
    </h1>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  data: vm => ({
    msg: vm.$t('home.title'),
  }),
}
</script>

<style lang="scss" scoped>
.home {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  align-content: center;
  justify-content: center;
  height: 100%;
  &__title {
    margin-top: 24px;
  }
}
</style>
