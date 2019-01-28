<template>
  <header>
      <h1 v-on:click="changeTitle">{{title}}</h1>
  </header> 
</template>

<script>


export default {

  props:{
    'title':String
  },
  
  data(){
    return {
     
     }
  },
  methods:{
    changeTitle: function(){
      this.$emit('changeTitle',"Vue Wizards");
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header{
    background: lightgreen;
    padding: 10px;
}

h1{
    color:#222;
    text-align: center;
}
</style>
