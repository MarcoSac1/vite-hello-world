<script>
import AppTitle from './components/AppTitle.vue';

export default {
  components:{
    AppTitle,
  },
  data(){
    return{
      message: 'ciao'
    }
  },
}
</script>

<template>
  
    <h1>

      {{ message }}

    </h1>
    <AppTitle/>
</template>

<style scoped>

</style>
