<template>
  <div class="home">
    <section class="home__section">
      <img class="home__img-mountains" src="../assets/mountains.png"/>
      <img class="home__img-grass" src="../assets/grass.png"/>
      <h1>Welcome!</h1>
    </section>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style lang="scss" scoped>
.home {

  height: 100vh;
  overflow-x: hidden;
  overflow-y: auto;
  perspective: 0.625rem;

  &__section {
    align-items: center;
    display: flex;
    height: 100%;
    justify-content: center;
    position: relative;
    transform-style: preserve-3d;
    z-index: -1;
  }

  &__img-mountains {
    height: 100%;
    object-fit: cover;
    object-position: center;
    position: absolute;
    width: 100%;
    z-index: -1;
  }

  &__img-grass {
    position: absolute;
    bottom: 0;
  }
    
}

</style>

