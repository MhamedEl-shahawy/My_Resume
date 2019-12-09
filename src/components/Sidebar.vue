<template>
  <div class="sidebar">
    <div class="sidebar__myimg-me">
      <img src="../assets/me.jpg"  class="sidebar__myimg-me_official" />
    </div>
    <div class="sidebar__info">
      <div class="sidebar__info_show">
          <code class="sidebar__info_name_p"><span class="var" >const</span> <span class="white">name =</span> "Mohamed Shahawy"</code>
      </div>
        <div class="sidebar__info_show">
          <code class="sidebar__info_name_p"><span class="var" >const</span> <span class="white"> personalInfo = </span> <span class="white" > { <br/></span>
          <pre>      <span class="blue">email</span><span class="white">:</span> "mohamedelshahawy599@gmail.com",
        <span class="blue">mobile</span><span class="white">:</span> "01117331413",
        <span class="blue">address</span><span class="white">:</span> "Damietta, Egypt."</pre><span class="white"> } </span>
          </code>
      </div>
          <div class="sidebar__info_show">
          <code class="sidebar__info_name_p"><span class="var" >const</span> <span class="white"> experienceInYears  = </span> <span class="white" > { <br/></span>
          <pre>     <span class="blue"> amateur</span><span class="white">:</span> 1,
        <span class="blue">professional</span><span class="white">:</span> 1,
        <span class="blue">total</span><span class="white">:</span> <span class="var">this</span><span class="white">.amateur + </span><span class="var">this</span><span class="white">.professional  </span></pre><span class="white"> } </span>
          </code>
      </div>
        <div class="sidebar__info_show">
          <code class="sidebar__info_name_p"><span class="var" >const</span> <span class="white"> companies  = </span> <span class="white" > [ <br/></span>
          <pre>      "None"</pre><span class="white"> ] </span>
          </code>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
::-webkit-scrollbar {
    height: 5px;
}
::-webkit-scrollbar-thumb {
    border-radius: 10px;
    background: #5f9ea0;
}
::-webkit-scrollbar-track {
    background: #000;
}
.sidebar{
  background-color:#051010;  
  height:100%;
    width: 100%;
  padding:2em 2em;
  font-family: monospace;
  margin:auto;
}
.sidebar__myimg-me{
	width:150px;
	height:150px;
    border-radius:100%;
    border: 4px solid #5f9ea0;
    width: 10vmax;
    min-width: 120px;
    height: 10vmax;
    min-height: 120px;
    border-radius: 100%;
    padding: 2px;
    background-color: #fff;
    margin: 0 auto;

}
.sidebar__myimg-me_official{
    width: 100%;
    border-radius: 100%;
  height:100%;

}
.myimg-me_official::after{
	content:"";
	border:2px solid #fff;
}
.sidebar__info{
   width:100%;
}
.sidebar__info_show{
	color:#a5c261;
	background-color:#232323;
	padding:7px;
	margin-top:2.2em;
   overflow-x: auto;
}
.var{
	color:#c26230;
}
.white{
    color:#fff;
}
.blue{
	color:#6d9cbe;
}
@media screen and (max-width:800px){
  .sidebar__myimg-me{
     width:200px;
     height:200px;
   }
  .sidebar{
    padding:2.3em 2.3em;
  }
} 
</style>
