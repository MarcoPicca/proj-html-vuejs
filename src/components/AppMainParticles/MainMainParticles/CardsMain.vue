<template >
    <section class="box-card-main-main">
        <div class="card">
            <img class="img-card" src="../../../assets/img/avada-nightclub-events-6-200x113.jpg" alt="">
            <h3>DJ Fusion</h3>
            <h4>August 19,2024 @ 8.00pm</h4>
        </div>
        <div class="card">
            <img class="img-card" src="../../../assets/img/avada-nightclub-events-5-200x113.jpg" alt="">
            <h3>House Nation</h3>
            <h4>August 19,2024 @ 8.00pm</h4>
        </div>
        <div class="card">
            <img class="img-card" src="../../../assets/img/avada-nightclub-events-4-200x113.jpg" alt="">
            <h3>Jazz Night</h3>
            <h4>August 19,2024 @ 8.00pm</h4>
        </div>
        <div class="card">
            <img class="img-card" src="../../../assets/img/avada-nightclub-events-3-200x113.jpg" alt="">
            <h3>VIP Taster Sessions</h3>
            <h4>August 19,2024 @ 8.00pm</h4>
        </div>
        <div class="card">
            <img class="img-card" src="../../../assets/img/avada-nightclub-events-2-200x113.jpg" alt="">
            <h3>Funky House Rave</h3>
            <h4>August 19,2024 @ 8.00pm</h4>
        </div>
        <div class="card">
            <img class="img-card" src="../../../assets/img/avada-nightclub-events-1-200x113.jpg" alt="">
            <h3>Urban Vibes</h3>
            <h4>August 19,2024 @ 8.00pm</h4>
        </div>
    </section>
</template>


<script>
export default {
    name: 'CardsMain',
}
</script>


<style lang="scss" scoped>
    .box-card-main-main{
        width: 56%;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        align-items: center;
    }

    .card{
        width: calc(( 100% / 3 ) - 2rem);
        height: 200px;
        margin-bottom: 2rem;
    }

    .img-card{
        width: 100%;
    }

    h3{
        width: 100%;
        height: 15px;
        padding: .3rem;
        color: #f63c81;
        text-transform: uppercase;
        font-size: 15px;
        margin-bottom: .3rem;
    }

    h4{
        width: 100%;
        height: 15px;
        padding: .3rem;
        color: white;
        font-size: 10px;
        font-weight: bold;
    }

    
</style>