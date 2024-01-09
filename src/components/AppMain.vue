<template >
    <HeaderMain />
    
    <MainMain />

    <FooterMain />
</template>


<script>
import HeaderMain from './AppMainParticles/HeaderMain.vue';
import MainMain from './AppMainParticles/MainMain.vue';
import FooterMain from './AppMainParticles/FooterMain.vue';

export default {
    name: 'AppMain',

    components: {
        HeaderMain,
        MainMain,
        FooterMain
    }
}
</script>


<style lang="scss" scoped>
    

</style>