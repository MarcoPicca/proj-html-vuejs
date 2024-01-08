<script>
 // 1 IMPORTO I COMPONENTI CHE UTILIZZERO'  -->
    import AppHeader from './components/AppHeader.vue';
    import AppMain from './components/AppMain.vue';
    import AppFooter from './components/AppFooter';
   

    export default{
  // 2 SETTARE IN EXPORT DEFAULT 
  // DATA, METHODS, CREATE O MOUNT O COMANDO DEDICATO E COMPONENTS  -->
      
  
        data() {
          return{
            
          }
        },


        methods: {
          
    
       
        },

        


        components: {
          AppHeader,
          AppMain,
          AppFooter
        }
          
    }
</script>

<template>
  <AppHeader />
  
  <AppMain />
  
  <AppFooter />
</template>

<style>

</style>