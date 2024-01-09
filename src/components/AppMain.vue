<template >
    <section id="img-bg-header-main">
        <div class="empty-space"></div>
        <h4>welcome to avada</h4>
        <h2>have the night of your life</h2>
        <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Explicabo dolores non nulla odio eligendi esse amet quaerat, atque assumenda dolorem eius alias aliquam impedit magni quidem doloremque corporis quia consectetur!
        </p>
        <CardHeaderMain />
    </section>
    <DjCards />
</template>


<script>
import CardHeaderMain from './AppMainParticles/CardHeaderMain.vue';
import DjCards from './AppMainParticles/DjCards.vue';

export default {
    name: 'AppMain',

    components: {
        CardHeaderMain,
        DjCards,
    }
}
</script>


<style lang="scss" scoped>
    #img-bg-header-main{
    background-image: url(../assets/img/avada-nightclub-cloud-background.jpg);
    background-position: center;
    background-size: contain;
    width: 100%;
    height: 1200px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .empty-space{
    width: 100%;
    height: 200px;
  }

  h4{
    text-transform: uppercase;
    font-weight: bold;
    color: #46b1fd;
    margin-bottom: .2rem;
  }

  h2{
    color: white;
    font-size: 45px;
    font-weight: 500;
    margin-bottom: 1rem;
  }

  p{
    width: 35%;
    font-size: 13px;
    color: gray;
    text-align: center;
    line-height: 1.3;
    margin-bottom: 2.5rem;
  }

</style>