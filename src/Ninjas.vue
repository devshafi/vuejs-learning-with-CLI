<template>
  <div>

      <h1>The ninjas list</h1>
       <ul>
      <li v-for="ninja in ninjas" :key="ninja">{{ninja}}</li>
  </ul>
  </div>
 
</template>

<script>


export default {
  
  data(){
    return {
      ninjas: ['Yoshi','Mario','Ryu']
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
    color: purple
}
</style>
