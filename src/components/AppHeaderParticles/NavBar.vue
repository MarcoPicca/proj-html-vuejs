<template >
    <div class="container">
        <div class="content-navbar">home</div>
        <div class="content-navbar">the club</div>
        <div class="content-navbar mr">events</div>
        <img class="img-nav" src="../../assets/img/avada-nightclub-logo-2x-300x99.png" alt="">
        <div class="content-navbar ml">jobs</div>
        <div class="content-navbar">news</div>
        <div class="content-navbar">contact us</div>
    </div>
</template>


<script>

export default {
    name: 'NavBar',
}
</script>



<style lang="scss" scoped>

    .container{
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .img-nav{
        width: 16%;
    }

    .content-navbar{
        width: 7%;
        display: flex;
        justify-content: center;
        align-items: center;
        padding-top: 1rem;
        height: 99px;
        color: white;
        text-transform: uppercase;
    }

    .ml{
        margin-left: 1rem;
    }

    .mr{
        margin-right: 1rem;
    }
</style>