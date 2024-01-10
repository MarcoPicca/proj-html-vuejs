<template >
    <section class="container-footer-main">
        <div class="container-content-footer-main">
            <h4>become a vip tonight</h4>
            <h3>exclusive vip lounge</h3>
        </div>
        <div class="container-button">
            <button>join the club</button>
        </div>
    </section>
</template>


<script>
export default {
    
}
</script>


<style lang="scss" scoped>
    .container-footer-main{
        width: 100%;
        height: 220px;
        background-image: url(../../assets/img/avada-nightclub-vip-hero-new.jpg);
        background-position: center;
        background-size: cover;
        display: flex;
        
    }

    .container-content-footer-main{
        width: 60%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    h4{
        text-transform: uppercase;
        color: #46b1fd;
        font-size: 16px;
        margin-top: 3rem;
    }

    h3{
        color: white;
        font-size: 58px;
        margin-left: 18.2rem;
    }

    .container-button{
        width: 40%;
        height: 100%;
        display: flex;
        align-items: center;
    }

    button{
        width: 170px;
        height: 45px;
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