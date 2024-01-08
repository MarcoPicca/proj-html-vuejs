<template>
  <div id="img-bg-header">
        <NavBar />
  </div>
</template>

<script>
  import NavBar from './particles/NavBar.vue';

  export default {
    name: 'AppHeader',

    data(){
        return {
        }
    },
    methods: {
        
    },
    components: {
      NavBar
    }
}
</script>


<style lang="scss" scoped>

  #img-bg-header{
    background-image: url(../assets/img/avada-nightclub-home-hero.jpg);
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 900px;
  }
</style>
