<template>
  <div>
    <app-header></app-header>

    

    <app-footer></app-footer>
  </div>
</template>

<script>


// registering components locally
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';


export default {
  
  components:{
    'app-header': Header,
    'app-footer': Footer
  },

  data(){
    return {
      title:'Ninja App!'
    }
  }
  
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
    color: green
}
</style>
