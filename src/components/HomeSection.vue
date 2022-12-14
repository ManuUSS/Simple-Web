<template>
    <div class="home">
    <NavBar/>
    <section class="home__section">
      <img class="home__img-background" src="../assets/bg.png"/> 
      <img class="home__img-mountains3" src="../assets/mt3.png"/>
      <img class="home__img-mountains" src="../assets/mt1.png"/> 
      <img class="home__img-mountains2" src="../assets/mt2.png"/>
      <img class="home__img-grass" src="../assets/grass.png"/>
      <h1>Welcome!</h1>
    </section>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar.vue'

export default {
    components: {
        NavBar
    },
    name: 'HomeSection'
}
</script>
<style lang="scss" scoped>
.home {

  height: 100vh;
  overflow-x: hidden;
  overflow-y: auto;
  perspective: 0.9375rem;

  &__section {
    align-items: center;
    display: flex;
    height: 100%;
    justify-content: center;
    position: relative;
    transform-style: preserve-3d;
    z-index: -1;
    //overflow: hidden;
  }

  &__img-background {
    object-fit: cover;
    object-position: center;
    top: 0;
    position: absolute;
    width: 100%;
    z-index: -2;
    transform: translateZ(-16px) scale(2.1);
  }

  &__img-mountains3 {
    object-fit: cover;
    object-position: center;
    top: 0.75rem;
    position: absolute;
    width: 100%;
    z-index: -1;
    transform: translateZ(-10px) scale(1.8);
  }


  &__img-mountains {
    object-fit: cover;
    object-position: center;
    bottom: -7.5rem;
    position: absolute;
    width: 100%;
    z-index: -1;
    transform: translateZ(-7px) scale(1.7);
  }

  &__img-mountains2 {
    object-fit: cover;
    object-position: center;
    left: 0;
    bottom: -0.625rem;
    position: absolute;
    width: 28%;
    z-index: -1;
    transform: translateZ(-3px) scale(1.8);
  }


  &__img-grass {
    bottom: 0;
    position: absolute;
    width: 78%;
    z-index: -1;
    transform: translateZ(-2px) scale(1.6);
  }

  h1 {
    color: #fff;
    font-size: 6.875rem;
    font-weight: 700;
    letter-spacing: 0.1rem;
    user-select: none;
  }
    
}

</style>
