<template>
  <footer>
    <p>{{copyright}} {{title}}</p>
  </footer>
</template>

<script>


// registering components locally

export default {

  props:{ 
    title:{
      type:String
    }
  },
  
  data(){
    return {
      copyright:'Copyright 2017'
    }
  }
  
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer{
  background: #222;
  padding: 6px;
}

p{
  color: lightgreen;
  text-align: center;
}

</style>
