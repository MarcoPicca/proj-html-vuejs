<template>
  <div id="img-bg-header">
        <NavBar />
        <MainHeader />
  </div>
</template>

<script>
  import NavBar from './AppHeaderParticles/NavBar.vue';
  import MainHeader from './AppHeaderParticles/MainHeader.vue';

  export default {
    name: 'AppHeader',

    data(){
        return {
        }
    },
    
    components: {
      NavBar,
      MainHeader
    }
}
</script>


<style lang="scss" scoped>

  #img-bg-header{
    background-image: url(../assets/img/avada-nightclub-home-hero.jpg);
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 940px;
  }
</style>
