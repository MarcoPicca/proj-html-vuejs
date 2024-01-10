<template>
    <section class="container-footer">
        <div class="container-column">
            <div class="col mt">
                <h4>events</h4>
                <article class="content-footer">
                    <img src="../assets/img/avada-nightclub-events-6-66x66.jpg" alt="">
                    <div class="content-text">
                        <h3>DJ Fusion</h3>
                        <h5>August 19, 2024 @ 8.00 pm</h5>
                    </div>
                </article>
                <article class="content-footer">
                    <img src="../assets/img/avada-nightclub-events-5-66x66.jpg" alt="">
                    <div class="content-text">
                        <h3>House Nation</h3>
                        <h5>August 19, 2024 @ 8.00 pm</h5>
                    </div>
                </article>
                <article class="content-footer mb">
                    <img src="../assets/img/avada-nightclub-events-4-66x66.jpg" alt="">
                    <div class="content-text">
                        <h3>Jazz Night</h3>
                        <h5>August 19, 2024 @ 8.00 pm</h5>
                    </div>
                </article>
                <p>View All Events</p>
            </div>
            <div class="col">
                <img class="mb" src="../assets/img/avada-nightclub-logo-2x-300x99.png" alt="">
                <div class="box-text-footer">
                    <h5>Avada NightClub</h5>
                    <h5>100 Nightclub Blvd</h5>
                    <h5>Beverly Hills Chiuaua</h5>
                    <h5 class="blue">Hi@your-domain.com</h5>
                    <h5>+1 (555) 000 000</h5>
                </div>
                <div class="box-icon">
                    <i class="fa-brands fa-facebook-f fa-sm" style="color: gray;"></i>
                    <i class="fa-brands fa-twitter fa-sm" style="color: gray;"></i>
                    <i class="fa-brands fa-instagram fa-sm" style="color: gray;"></i>
                    <i class="fa-brands fa-youtube fa-sm" style="color: gray;"></i>
                </div>
            </div>
            <div class="col mt">
                <h4>venues</h4>
                <img class="img" src="../assets/img/avada-nightclub-footer-rooftop-400x171.jpg" alt="">
                <img class="img" src="../assets/img/avada-nightclub-footer-dancelounge-400x171.jpg" alt="">
            </div>
        </div>
    </section>
</template>


<script>
export default {
   name: 'AppFooter',
}
</script>


<style lang="scss" scoped>
    .container-footer{
        width: 100%;
        height: 600px;
        background-image: url(../assets/img/avada-nightclub-footer-background-final-2.jpg);
        background-position: bottom;
        background-size: cover;
        display: flex;
        justify-content: center;
    }

    .container-column{
        width: 80%;
        height: 70%;
        display: flex;
        margin-top: 3rem;
    }

    .col{
        width: calc( 100% / 3 );
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    h4{
        color: white;
        text-transform: uppercase;
        font-weight: lighter;
        margin-bottom: 2rem;
    }

    .content-footer{
        width: 90%;
        height: 68px;
        margin-bottom: 1.5rem;
        display: flex;
    }

    .content-text{
        width: 70%;
        height: 100%;
        text-align: center;
    }

    h3{
        font-size: 25px;
        color: #46b1fd;
        margin-top: .3rem;
        margin-bottom: .6rem;
    }
    
    h5{
        color: gray;
        margin-bottom: .2rem;
    }

    p{
        color: #0b7ccd;
        margin-top: 1.6rem;
    }

    .mb{
        margin-bottom: 3rem;
    }

    .mt{
        margin-top: 2rem;
    }

    .box-text-footer{
        width: 60%;
        height: 130px;
        text-align: center;
        margin-bottom: .7rem;
    }

    .blue{
        color: #0b7ccd;
    }

    .box-icon{
        width: 40%;
        height: 30px;
        display: flex;
        justify-content: space-around;
    }

    .img{
        width: 87%;
        margin-bottom: 2rem;
    }
</style>