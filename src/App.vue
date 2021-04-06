<template>
  <div id="app">
    <div class="container-fluid">
      <ul>
        <li><a href="https://vuejs.org" target="_blank" rel="noopener">Home</a></li>
        <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">about</a></li>
        <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Contact us</a></li>
        <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Social Media</a></li>
      </ul>
    </div>
    
    
    <img alt="Vue logo" src="./assets/img1.jpg">
    <HelloWorld msg="Mari Belajar"/>
      
      <p>Pembelajaran</p>
     
  </div>
</template>



<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  margin-top: 60px;
}


ul {
  padding-top: 10px;
  background-color: rgb(120, 221, 221);
  height: 30px;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color:rgb(0, 0, 0);
}
</style>
