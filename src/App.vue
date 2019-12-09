<template>
  <div class="app">
    <Sidebar />
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Sidebar from './components/Sidebar.vue'


export default {
  name: 'app',
  components: {
    HelloWorld,
    Sidebar
  }
}
</script>
<style>
::selection{
  color: #e6e1dc;
  background-color:#000;
}
body::-webkit-scrollbar-track {
    background: #000;
}

body::-webkit-scrollbar{
    width: 7px;
    height: 7px;
}

body::-webkit-scrollbar-thumb {
    border-radius: 10px;
    background: #FFE70B;
}
body{
  height:100%;
  width:100%;
  overflow-x:hidden;
}
*{
  padding:0;
  margin:0;
  box-sizing:border-box;
}
.app {
  width:100%;
  height:100%;
  display:grid;
  grid-template-columns:1fr 3fr;
}
@media screen and (max-width:800px){
  .app{
     display:block;
  }
} 
</style>
