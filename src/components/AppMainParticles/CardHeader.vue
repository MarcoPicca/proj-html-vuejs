<template>
    <div class="cardbox">
        <section class="container-card dance-lounge">
            <h4 class="text">dance lounge</h4>
            <hr class="line-blue"></hr>
        </section>
        <section class="container-card rooftop-bar">
            <h4 class="text">rooftop bar</h4>
            <hr class="line-red"></hr>
        </section>
        <section class="container-card vip-lounge">
            <h4 class="text">vip lounge</h4>
            <hr class="line-gold"></hr>
        </section>
        <section class="container-card resident-dj">
            <h4 class="text">resident dj</h4>
            <hr class="line-blue"></hr>
        </section>
    </div>
</template>


<script>
export default {
    name: 'CardHeader',
}
</script>


<style lang="scss" scoped>
    .cardbox{
        width: 54%;
        display: flex;
        flex-wrap: wrap;
    }

    .container-card{
        width: 50%;
        height: 330px;
        display: flex;
        justify-content: space-between;
        align-items: end;
    }

    .dance-lounge{
        background-image: url(../../assets/img/avada-nightclub-dancelounge-small.jpg);
        background-position: center;
        background-size: cover;
    }

    .rooftop-bar{
        background-image: url(../../assets/img/avada-nightclub-rooftoplounge-small.jpg);
        background-position: center;
        background-size: cover;
    }

    .vip-lounge{
        background-image: url(../../assets/img/avada-nightclub-viplounge-small.jpg);
        background-position: center;
        background-size: cover;
    }

    .resident-dj{
        background-image: url(../../assets/img/avada-nightclub-events-small.jpg);
        background-position: center;
        background-size: cover;
    }

    .text{
        width: 45%;
        color: white;
        padding-left: 2rem;
        margin-bottom: 1.6rem;
        font-size: 25px;
    }

    .line-blue{
        width: 55%;
        height: 1px;
        color: #46b1fd;
        background-color: #46b1fd;
        margin-bottom: 2.3rem;
    }

    .line-red{
        width: 55%;
        height: 1px;
        color: #f63c81;
        background-color: #f63c81;
        margin-bottom: 2.3rem;
    }

    .line-gold{
        width: 55%;
        height: 1px;
        color: gold;
        background-color: gold;
        margin-bottom: 2.3rem;
    }
</style>