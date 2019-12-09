<template>
  <div class="content">
     <nav clas="content__navigate">
        <p class="content__navigate_p">jumb to:</p>
        <ul class="content__navigate_filter">
          <li class="content__navigate_filter_li_item"><a class="content__navigate_filter_li_item"  href="#how">How I Coded Along The Past 2 Years - </a></li>
          <li class="content__navigate_filter_li_item"><a class="content__navigate_filter_li_item"  href="#helping"> Helping Tools - </a></li>
          <li class="content__navigate_filter_li_item"><a class="content__navigate_filter_li_item"  href="#learning"> Currently Learning - </a></li>
          <li class="content__navigate_filter_li_item"><a class="content__navigate_filter_li_item"  href="#recursively"> Recursively Learning - </a></li>
          <li class="content__navigate_filter_li_item"><a class="content__navigate_filter_li_item"  href="#projects"> Some Projects and Contributions</a></li>
        </ul>
     </nav>
     <hr />
     <section class="how-coded" id="how">
        <h1 class="how-coded_h1">How I Coded Along The Past 2 Years:</h1>
        <div class="how-coded__pre">
           <h2 class="how-coded__pre_h2">Profession:</h2>
           <p class="langName">ES5</p>
           <pre>
            <code class="code"> <span class="orange">var</span> arr = [<span class="green">'vanillajs'</span>,<span class="green">'is'</span>,<span class="green">'plain'</span>,<span class="green">'js'</span>]; 
  arr = arr.map(<span class="orange">function</span> (word) {
    <span class="orange">return</span> word.toUpperCase();
 }); 
 arr = arr.join(' ');      
</code>  
           </pre>
        
            <p class="langName">React</p>
           <pre>
            <code class="code"><span class="orange">import</span>  React, { useState }<span class="orange"> from</span><span class="green"> react</span>
<span class="orange">import</span>  Logo <span class="orange"> from</span><span class="green"> '../logo/logo.jsx'</span>
<span class="orange">import</span> <span class="green"> './header.css'</span>  
<span class="orange">const</span> Header =  props => {
 <span class="orange">const</span> [showLogo, setShowLogo] = useState(true)
 <span class="orange"> if </span>(!props.showLogo) setShowLogo(false)
  <span class="orange">return </span>(
     {showLogo && hideLogo}
  )
  }
<span class="orange">export default </span>Header
</code>  
    </pre>
      <p class="langName">Vue.js</p>
     <pre>
  <code class="code"> <span class="orange">const</span>  App = <span class="orange"> new </span>Vue({
     <span class="blue">el</span>:<span class="green"> '#app'</span>
     store,
     <span class="blue">data</span>: {
        <span class="blue">products</span>: [],
    },
    <span class="blue">components</span>: {
        <span class="green">'product-card'</span>: productCard,
        <span class="green">'product-details'</span>: productDetails,
    },
    created() {
        <span class="orange">this</span>.$http
        .get(<span class="green">'https://reqres.in/api/products/3'</span>)
        .<span class="orange">then</span>(response => {
            <span class="orange">this</span>.products = response.data
        })
        },
    <span class="blue">computed</span>: {
        selectedProduct() {
        <span class="orange">return this</span>.$store.state.selectedProduct
        }
    }
 })
</code>  
           </pre>
             <p class="langName">ES6</p>
            <pre>
            <code class="code"> <span class="orange">let</span> arr = [<span class="green">'vanillajs'</span>,<span class="green">'is'</span>,<span class="green">'plain'</span>,<span class="green">'js'</span>]; 
 arr = arr.map(word => word.toUpperCase()).join(' ');
</code>  
           </pre>
       </div>   
     </section>
      <hr /> 
    <section class="helping" id="helping">
        <h1 class="helping_h1">Helping Tools:</h1>
      <div class="helping__tools">
       <img  class="helping__tools_img" src="../assets/webpack.png"  title="i use: webpack in my work" />
       <img  class="helping__tools_img" src="../assets/babel.png"  title="i use: babel in my work" />
       <img  class="helping__tools_img" src="../assets/sass.svg"  title="i use: sass in my work" />
       <img  class="helping__tools_img" src="../assets/postcss.png"  title="i use: postcss in my work" />
       <img  class="helping__tools_img" src="../assets/vuex.png"  title="i use: vuex in my work" />
       <img  class="helping__tools_img" src="../assets/git.png"  title="i use: git in my work" />
       <img  class="helping__tools_img" src="../assets/github.png"  title="i use: github in my work" />
      </div>
    </section>  
     <hr /> 
    <section class="learning" id="learning">
        <h1 class="learning_h1">Currently Learning:</h1>
      <div class="learning__technology">
       <img  class="learning__technology_img" src="../assets/jasmine.svg"  title="i use: jasmine in my work" />
       <img  class="learning__technology_img" src="../assets/nodejs.png"  title="i use: nodejs in my work" />
      </div>
    </section>  
       <hr /> 
    <section class="projects" id="projects">
        <h1 class="projects_h1">Some Projects and Contributions:</h1>
        <div class="projects__links">
        <a class="projects__links_link" href="https://ecomerce-f7095.firebaseapp.com/" target="_blank">Ecomerce</a>
        <a class="projects__links_link" href="https://ecommerce-shop-b216e.firebaseapp.com/" target="_blank">CinemaCrush</a>
        <a class="projects__links_link" href="https://chatapp-2743c.firebaseapp.com/" target="_blank">TechChat</a>
        <a class="projects__links_link" href="https://github.com/MhamedEl-shahawy/poster-shop" target="_blank">PosterShop</a>
        <a class="projects__links_link" href="https://mhamedel-shahawy.github.io/solo---creative-website/index.html" target="_blank">Solo</a>
        <a class="projects__links_link" href="https://mhamedel-shahawy.github.io/Loso-Responsive/" target="_blank">Loso</a>
        <a class="projects__links_link" href="https://mhamedel-shahawy.github.io/Landpage/" target="_blank">Altrntv</a>
        <a class="projects__links_link" href="https://mhamedel-shahawy.github.io/Kanox_Blog/" target="_blank">Kanox</a>
        </div>
    </section>        
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
.content{
  background-color:#f0cd06;  
  height:100%;
  width:100%;
  padding:3em;
  font-family: monospace;
    overflow-x:hidden;

}
.content__navigate{
  width:100%;
}
.content__navigate_p{
  font-size:2em;
  color:#696969;
}
.content__navigate_filter{
  list-style:none;
  margin-top:1.5em;
  width:100%;

}
.content__navigate_filter_li_item{
   color:#696969;
   text-decoration:none;
   font-size:1.2em;
   display:inline-block;
   line-height:2;
}
hr{
  display: block;
    unicode-bidi: isolate;
    margin-block-start: 0.5em;
    margin-block-end: 0.5em;
    margin-inline-start: auto;
    margin-inline-end: auto;
    overflow: hidden;
    border-style: inset;
    border-width: 1px;
    margin-top:0.5em;
}
.how-coded{
   width:100%;
   margin-top:2em;
}
.how-coded__pre_h2{
  margin-top:1em;  
  margin-bottom:1em;  
}
.langName{
  margin: 0 1px;
border-top-right-radius: 10px;
border-top-left-radius: 10px;
position: relative;
top: 24px;
font-size: 12px;
padding: 4px 10px;
background-color: grey;
color: #fff;
font-family: MerriweatherSansRegular;
}
.code{
      display: block;
    overflow-x: auto;
    padding: 0.5em;
    background: #232323;
    color: #e6e1dc;
    border: 1px solid #fff;
    border-radius: 10px;
}
.helping__tools,
.learning__technology{
   display:flex-inline;
   justify-conent:space-around;
   flew-wrap:wrap;
}
.helping_h1,
.learning_h1,
.projects_h1{
   margin-top:1em;

}
.helping__tools_img,
.learning__technology_img{
    max-width: 300px;
    max-height: 100px;
    margin:2em;
}
.projects__links{
  margin-top:2em;
}
.projects__links_link{
    color: #000;
    font-family: MerriweatherSansRegular;
    font-size:1.3em;
    margin-right:1em;
    line-height:2;
}
.projects__links_link::after{
    display: inline-block;
    content: '';
    background-repeat: no-repeat;
    background-image: url(data:image/svg+xml;base64,PHN2ZyBjbGFzcz0iaWNvbiBpY29uLWV4dGVybmFsLWxpbmsiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjI4IiBoZWlnaHQ9IjI4IiB2aWV3Qm94PSIwIDAgMjggMjgiIGFyaWEtaGlkZGVuPSJ0cnVlIj48cGF0aCBkPSJNMjIgMTQuNXY1YzAgMi40ODQtMi4wMTYgNC41LTQuNSA0LjVoLTEzQTQuNTAyIDQuNTAyIDAgMCAxIDAgMTkuNXYtMTNDMCA0LjAxNiAyLjAxNiAyIDQuNSAyaDExYy4yODEgMCAuNS4yMTkuNS41djFjMCAuMjgxLS4yMTkuNS0uNS41aC0xMUEyLjUwNyAyLjUwNyAwIDAgMCAyIDYuNXYxM0MyIDIwLjg3NSAzLjEyNSAyMiA0LjUgMjJoMTNjMS4zNzUgMCAyLjUtMS4xMjUgMi41LTIuNXYtNWMwLS4yODEuMjE5LS41LjUtLjVoMWMuMjgxIDAgLjUuMjE5LjUuNXpNMjggMXY4YzAgLjU0Ny0uNDUzIDEtMSAxYS45OS45OSAwIDAgMS0uNzAzLS4yOTdsLTIuNzUtMi43NUwxMy4zNiAxNy4xNGMtLjA5NC4wOTQtLjIzNC4xNTYtLjM1OS4xNTZzLS4yNjYtLjA2My0uMzU5LS4xNTZsLTEuNzgxLTEuNzgxYy0uMDk0LS4wOTQtLjE1Ni0uMjM0LS4xNTYtLjM1OXMuMDYzLS4yNjYuMTU2LS4zNTlMMjEuMDQ4IDQuNDU0bC0yLjc1LTIuNzVhLjk5Ni45OTYgMCAwIDEtLjI5Ny0uNzAzYzAtLjU0Ny40NTMtMSAxLTFoOGMuNTQ3IDAgMSAuNDUzIDEgMXoiLz48L3N2Zz4K);
    background-size: 12px;
    width: 12px;
    height: 20px;
    margin-top: 7px;
    margin-left: 3px;
    vertical-align: text-top;
}
.orange{
  color:#c26230;
}
.green{
   color:#a5c261;
}
.blue{
  color:#6d9cbe;
}
@media screen and (max-width:450px){
  .content{
    padding:1em;
    padding-top:2em;
  }
  .helping__tools,
  .learning__technology{
   display:block;
   text-align:center;
  }
  .helping__tools_img,
  .learning__technology_{
   display:block;
   margin:auto;
   margin-bottom:2em;
  }
  .projects__links{
    display:grid;
    grid-template-columns:repeat(2,1fr);
  }
  .projects__links_link{
     line-height:2;
  }
}
@media screen and (max-width:800px){
  .content__navigate_filter_li_item{
   font-size:1.1em;
  }
    .helping__tools_img,
    .learning__technology_img{
    max-width: 250px;
    max-height: 100px;
  }
}
</style>
