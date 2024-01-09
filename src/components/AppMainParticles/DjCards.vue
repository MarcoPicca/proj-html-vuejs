<template>
    <div class="box-dj-cards">
        <section class="container-dj-card resident-dj">
            <h4>resident dj</h4>
            <h3>dj avada</h3>
            <button>view profile</button>
        </section>
        <section class="container-dj-card guest-dj">
            <h4>special guest dj</h4>
            <h3>dj blondie</h3>
            <button>view profile</button>
        </section>
    </div>
</template>



<script>
export default {
    name: 'DjCards',

}
</script>


<style lang="scss" scoped>
    .box-dj-cards{
        width: 100%;
        display: flex;
        justify-content: center;
    }

    .container-dj-card{
        width: 50%;
        height: 530px;
        padding: 1.5rem;
        border-top: 4px solid #46b1fd;
    }

    .container-dj-card:hover{
        border-top: 4px solid #f63c81;
    }

    .resident-dj{
        background-image: url(../../assets/img/avada-nightclub-resident-profile.jpg);
        background-position: center;
        background-size: cover;
    }

    .guest-dj{
        background-image: url(../../assets/img/avada-nightclub-lisahouse-inset-new.jpg);
        background-position-x: center;
        background-position-y: top;
        background-size: cover;
    }
</style>