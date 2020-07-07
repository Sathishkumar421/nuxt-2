<template>
<div style="width:100%; margin: 0 auto">
  <div class="container-fluid">
    <div class="row">
      <img src="~/assets/Img/about.png" alt="about_facilio" class="aboutFacilio">
    </div>
    <div class="row buttons">
      <button type="button" class="btn btn-outline-info col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3" data-toggle="button" aria-pressed="false" autocomplete="off">
      Contextual Maintenance
      </button>
      <button type="button" class="btn btn-outline-info col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3" data-toggle="button" aria-pressed="false" autocomplete="off">
      Predictive Sustainability
      </button>
      <button type="button" class="btn btn-outline-info col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3" data-toggle="button" aria-pressed="false" autocomplete="off">
      Connected Energy
      </button>
      <button type="button" class="btn btn-outline-info col-xs-6 col-sm-4 col-md-3 col-lg-3 col-xl-3" data-toggle="button" aria-pressed="false" autocomplete="off">
      Facilio Kiosk
      </button>
    </div>
    <div class="row cards">
      <div class="card  col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6" >
        <img class="card-img-top" src="~/assets/Img/ab1.png" alt="Card image cap">
          <div class="card-body">
           <p class="card-text"> From the moment you add Facilio to your buildings, it automatically tracks your asset performance trend, visualises spaces dynamically, knows where and when you require repair or inspection, and lets you effectively prioritize schedules.</p>
          </div>
      </div>
      <div class="card  col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6" >
        <img class="card-img-top" src="~/assets/Img/ab2.png" alt="Card image cap">
          <div class="card-body">
           <p class="card-text">Facilio uses IoT and ML to directly interface and automatically comb through energy data across your portfolio.</p>
          </div>
      </div>
      <div class="card col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6" >
        <img class="card-img-top" src="~/assets/Img/ab3.png" alt="Card image cap">
          <div class="card-body">
           <p class="card-text">With Facilio, equip technicians with real-time problem data and let everyone collaborate at any given time. Get your teams up to speed without having to send a bunch of emails, reminders and service descriptions</p>
          </div>
      </div>
      <div class="card  col-xs-12 col-sm-12 col-md-12 col-lg-6 col-xl-6">
        <img class="card-img-top" src="~/assets/Img/ab4.png" alt="Card image cap">
          <div class="card-body">
           <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
      </div>

    </div>
  </div>
</div>

</template>

<script>
export default {
  name:'About',
  data(){
    return{
      
  }
}
}
</script>

<style>

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.aboutFacilio{
  width:100%;
  height:inherit;
}
 
 .buttons{
   display:flex;
   justify-content: center;
   margin:30px 30px;
   height:100%;
  font-style:inherit;
 }
 .btn{
   margin: 15px 30px;
   max-width:200px;
   background-color: rgb(73, 26, 117);
   color:floralwhite;
 }

 .cards{
   display:flex;
   justify-content:center;
   font-style:inherit;
   margin:0 auto;
 }
 .card{
   margin:10px 20px;
   max-height:700px;
   max-width:500px;
 }
 .card-img-top{
   height:350px;
   max-width:350px;
  }
</style>
