<template>
    <section class="container-footer">
        <div class="container-column">
            <div class="col mt">
                <h4>events</h4>
                <article class="content-footer">
                    <img class="img-scale" src="../assets/img/avada-nightclub-events-6-66x66.jpg" alt="">
                    <div class="content-text">
                        <h3>DJ Fusion</h3>
                        <h5>August 19, 2024 @ 8.00 pm</h5>
                    </div>
                </article>
                <article class="content-footer">
                    <img class="img-scale" src="../assets/img/avada-nightclub-events-5-66x66.jpg" alt="">
                    <div class="content-text">
                        <h3>House Nation</h3>
                        <h5>August 19, 2024 @ 8.00 pm</h5>
                    </div>
                </article>
                <article class="content-footer mb">
                    <img class="img-scale" src="../assets/img/avada-nightclub-events-4-66x66.jpg" alt="">
                    <div class="content-text">
                        <h3>Jazz Night</h3>
                        <h5>August 19, 2024 @ 8.00 pm</h5>
                    </div>
                </article>
                <h5 class="blue">View All Events</h5>
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
                    <i class="fa-brands fa-facebook-f fa-sm icon" style="color: gray;"></i>
                    <i class="fa-brands fa-twitter fa-sm icon" style="color: gray;"></i>
                    <i class="fa-brands fa-instagram fa-sm icon" style="color: gray;"></i>
                    <i class="fa-brands fa-youtube fa-sm icon" style="color: gray;"></i>
                </div>
            </div>
            <div class="col mt">
                <h4>venues</h4>
                <img class="img" src="../assets/img/avada-nightclub-footer-rooftop-400x171.jpg" alt="">
                <img class="img" src="../assets/img/avada-nightclub-footer-dancelounge-400x171.jpg" alt="">
            </div>
        </div>
        <div class="container-copyright">
            <div class="empty-space"></div>
            <div class="copyright">
                © Copyright 2012-2021 | Avada Theme by <h5 class="blue">ThemeFusion</h5> | All Rights Reserved | Powered by <h5 class="blue big-mr">Cataclism</h5>
            </div>
            <button><i class="fa-solid fa-chevron-up fa-xl" style="color: #ffffff;"></i></button>
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
        flex-wrap: wrap;
    }

    .container-column{
        width: 80%;
        height: 70%;
        display: flex;
        margin-top: 3rem;
        margin-bottom: 3rem;
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
        font-weight: bold;
        font-size: 17px;
        margin-bottom: 2rem;
    }

    .content-footer{
        width: 90%;
        height: 68px;
        margin-bottom: 1.5rem;
        display: flex;
    }

    .content-footer:hover .img-scale{
        scale: 1.2;
        transition: .3s;
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

    h3:hover{
        color: #f63c81;
    }
    
    h5{
        color: gray;
        margin-bottom: .2rem;
        margin-left: .3rem;
        margin-right: .3rem;
    }

    h5:hover{
        color: white;
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

    .img:hover{
        scale: 1.2;
        transition: .3s;
    }

    .container-copyright{
        width: 100%;
        height: 70px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: 13px;
        color:  gray;
    }

    .copyright{
        width: 50%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    button{
        width: 45px;
        height: 45px;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgb(65, 65, 65);
        margin-right: 2rem;
    }

    .empty-space{
        width: 6%;
        height: 100%;
    }
</style>