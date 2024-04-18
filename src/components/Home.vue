<script>
import '../bootstrap5/css/bootstrap.min.css'
export default {
  data(){
    return{
      name:"Marie May Estorgio",
      profile:'../src/img/maye.jpg'
    }

  }
}
</script>
<template>
<div class="container mt-5">
  <div class="row">
    <div class="col-lg-12 ">
      <main>
  <img :src="profile" alt="Marie May Estorgio" class="img-fluid d-none d-sm-block" >
  <h1 >Hello <span id="wave">👋</span></h1>
  <h2 class="text-center">I am {{name}}</h2>
  <h3 class="text-center">Backend Developer 😊</h3>
  
  <span id="line1"></span>
  <div id="line2"></div>
<span id="line1"></span>
  
  <RouterLink class="btn btn-primary" to="/about">More About Me.</RouterLink>
</main>
    </div>
  </div>
</div>
</template>

<style scoped>
  main{
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
   
  }
     @keyframes wave {
    0% { transform: rotate(0deg); }
    25% { transform: rotate(30deg); }
    50% { transform: rotate(0deg); }
    75% { transform: rotate(-30deg); }
    100% { transform: rotate(0deg); }
  }
  #wave {
    display: inline-block;
    animation: wave 1s infinite;
  }
  img{
    border-radius: 50%;
    width: 200px;
    height: 200px;
    display: block;
    margin: 10px auto;
  }
  h1{
    color: coral;
    text-align: center;
  }#line1{
    height: 2px;
    width: 130px  !important;
    background: #000;
    margin: 10px 0;
    display: inline-block;
  }
  .btn{
    width:200px;
    display: block;
    margin: 0 auto;
  }
  #line2{
    width:20px;
    height: 20px;
    background: #000;
    display: inline-block;
    border-radius: 50%;
  }
  @media screen and (max-width: 768px) {
        h1 {
          font-size: 2rem;  
        }
        h2, h3 {
          font-size: 1rem;  
        }
       #line1{
        width: 90px !important;
       }.container{
        margin-top: 40px;
       }
       main{
        top:60%;
       }
      }
</style>