<template>
    <section class="img-bg-main-main">
        <h4>special events</h4>
        <h3>for your diary</h3>

        <CardsMain />

        <button>rsvp now</button>
    </section>
</template>


<script>
import CardsMain from './MainMainParticles/CardsMain.vue';

export default {
    name: 'MainMain',

    components: {
        CardsMain,
    }
}
</script>


<style lang="scss" scoped>
    .img-bg-main-main{
        background-image: url(../../assets/img/avada-nightclub-homepage-events-background-new.jpg);
        background-position: center;
        background-size: cover;
        width: 100%;
        height: 1100px;
        display: flex;
        flex-direction: column;
        align-items: center;
        position: relative;
    }

    

    h4{
        text-transform: uppercase;
        color: #f63c81;
        padding-top: 13.3rem;
        font-size: 13px;
    }

    h3{
        color: white;
        font-size: 38px;
        margin-bottom: 5rem;
    }

    button{
        width: 130px;
        height: 40px;
        text-transform: uppercase;
        color: white;
        background-color: #f63c81;
        border: none;
        margin-top: 2rem;
        font-weight: bolder;
    }

    button:hover{
        background-color: #46b1fd;
    }
</style>