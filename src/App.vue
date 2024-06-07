<script>
import AppTitle from "./components/Apptitle.vue";

export default {
  components:{
    AppTitle,
  },
  data(){
    return{
      count:0
    }
  }
}
</script>

<template>
  
  <main>
    <AppTitle/>
  </main>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

</style>
