<template>
    <section class="container-card-header-main">
        <CardHeader />
    </section>
</template>



<script>
import CardHeader from './CardHeader.vue';

export default {
    name: 'CardHeaderMain',

    components: {
      CardHeader,
    }
}
</script>



<style lang="scss" scoped>
    .container-card-header-main{
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
    }
</style>