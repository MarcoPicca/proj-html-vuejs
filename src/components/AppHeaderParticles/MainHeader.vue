<template>
    <section class="container">
        <img class="img-header" src="../../assets/img/avada-nightclub-homepage-image-600x298.png" alt="">
        
        <ExtraIcon />

        <div class="container-content-header">
            <h2>making memories all night long</h2>
            <button class="toform" @click="showForm = true">become a vip</button>
        </div>

        <Form v-if="showForm" @closeForm="showForm = false"/>

        <img class="img-footer-header" src="../../assets/img/avada-nightclub-play-showreel-200x47.png" alt="">
    </section>
</template>



<script>
import ExtraIcon from './ExtraIcon.vue';
import Form from './Form.vue';

export default {
    name: 'MainHeader',

    data() {
     return{
        showForm: false
     };
    },
  
    components: {
        ExtraIcon,
        Form
    }
}
</script>



<style lang="scss" scoped>
    .container{
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .img-header{
        width: 800px;
        height: 398px;
        border-bottom: 4px solid #46b1fd;
        margin-top: 4.8rem;
    }

    .container-content-header{
        width: 800px;
        height: 142.8px;
        background-color: rgb(0, 0, 0, 0.5);
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        position: relative;
        margin-bottom: 5rem;
        
    }

    h2{
        font-size: 40px;
    }

    button.toform{
        width: 140px;
        height: 37px;
        border: none;
        color: white;
        text-transform: uppercase;
        font-weight: bold;
        background-color: #f63c81;
        position: absolute;
        top: 124px;
    }

    

    button:hover{
        background-color: #46b1fd;
    }

    .img-footer-header{
        width: 17%;
    }

    .img-footer-header:hover{
        scale: 1.2;
        transition: .3s;
    }
</style>