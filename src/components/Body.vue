<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
 
 <compA contentA="COMPONENTA"/>

  <compB contentB="COMPONENTB"/>


  <compC contentC="COMPONENTC"/>

    <h3> Rock , Paper , Scissors ? </h3>

    
  
  </div>
</template>

<script>

import compA from './compA.vue'
import compB from './compB.vue'
import compC from './compC.vue'


export default {
  name: 'Body',
  components: {
  compA,
  compB,
  compC
 
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
