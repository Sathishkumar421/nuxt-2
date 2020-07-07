<template>
 <nav class="navbar navbar-expand-lg navbar-light ">
   <a class="navbar-brand" href="#">
    <img src="~/assets/Img/logo1.png" alt="brand-logo" name="brand-logo" width="70px" height="60px">
  </a>
  <button class="navbar-toggler " type="button" data-toggle="collapse" data-target="#toggle1" aria-controls="toggle1" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="toggle1">
    <ul class="navbar-nav mr-auto mt-2 mt-lg-0 ">
      <li class="nav-item active">
        <nuxt-link to="/" class= "nav-link ">Home</nuxt-link>
      </li>
      <li class="nav-item active">
        <nuxt-link to="/about" class="nav-link ">About</nuxt-link>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
  
</template>
<script>

export default {
 
 name: 'Navbar',
 data(){
   return{

   }
 },
 methods:[
 ]
}
</script>
<style>
 
.navbar{
  border-bottom:1px solid darkslateblue;
}

li:hover{
   border-bottom: 2px double darkslateblue;
}
 
li{
  padding:8px 20px;
} 
</style>
