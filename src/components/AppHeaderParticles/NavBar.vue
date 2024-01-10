<template >
    <div class="container">
        <div class="container-content-nav-bar">
            <div class="content-navbar home">home</div>
            <div class="content-navbar club">the club</div>
            <div class="content-navbar mr events">events</div>
        </div>
        <img class="img-nav" src="../../assets/img/avada-nightclub-logo-2x-300x99.png" alt="">
        <div class="container-content-nav-bar">
            <div class="content-navbar ml jobs">jobs</div>
            <div class="content-navbar news">news</div>
            <div class="content-navbar">contact us</div>
        </div>
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

    .container-content-nav-bar{
        width: 24%;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .content-navbar{
        width: 22%;
        display: flex;
        justify-content: center;
        align-items: center;
        padding-top: 1rem;
        color: white;
        text-transform: uppercase;
        font-size: 10px;
        font-weight: 800;
        
    }

    div.home{
        width: 10%;
    }

    div.club{
        width: 17%;
    }

    div.events{
        width: 14%;
    }

    div.jobs{
        width: 9%;
    }

    div.news{
        width: 9%;
    }

    .content-navbar:hover{
        border-bottom: 1px solid #f63c81;
        color: #f63c81;
    }

    .ml{
        margin-left: 1rem;
    }

    .mr{
        margin-right: 1rem;
    }
</style>