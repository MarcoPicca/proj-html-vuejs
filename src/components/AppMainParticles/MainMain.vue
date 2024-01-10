<template>
    <section class="img-bg-main-main">
        <h4>special events</h4>
        <h3>for your diary</h3>

        <CardsMain />

        <button @click="showForm = true">rsvp now</button>

        <Form v-if="showForm" @closeForm="showForm = false"/>
    </section>
</template>


<script>
import Form from '../AppHeaderParticles/Form.vue';
import CardsMain from './MainMainParticles/CardsMain.vue';

export default {
    name: 'MainMain',

    data() {
     return{
        showForm: false
     };
    },

    components: {
        CardsMain,
        Form
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