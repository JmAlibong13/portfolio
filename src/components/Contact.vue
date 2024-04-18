<script>
export default {
  
}
</script>
<template>
  <div class="container mt-5">
    <div class="row">
      <div class="col-lg-7 col-md-12">
        <h1>Contact Me</h1>
        <span>Have a project in mind or just want to say hello? Don't hesitate to get in touch! You can reach me through the following channels:</span>
        
       
        <span class="mt-5">Social Media :</span>
        <div id="line"></div>
       <img src="https://static.vecteezy.com/system/resources/previews/023/986/613/non_2x/facebook-logo-facebook-logo-transparent-facebook-icon-transparent-free-free-png.png" alt="">
       <img src="https://img.freepik.com/free-vector/instagram-icon_1057-2227.jpg?size=338&ext=jpg&ga=GA1.1.1700460183.1713052800&semt=ais" alt="">
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSS4UJP8NHuKjQ34J-SqrUsOkUn4LgI4TQwFA3vAtqkvw&s" alt="">
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNMIDTeZmw8byypgn7ZIzQknTgwPpwTr-6VuUihnaULg&s" alt="">
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQjk6zuEp6RZu3TMjnr1w1G0vgbyJi8GGFO2VLSjhmPA&s" alt="">
       <p class="mt-3">Looking forward to hearing from you! 😊</p>
      </div>
      <div class="col-lg-5 col-md-12">
        <form action="">
          <input type="text" class="form-control" placeholder="FullName">
          <input type="email" class="form-control" placeholder="Email">
          <span>Message :</span>
          <textarea name="" id="" cols="58" rows="7" class="form-control">
           
          </textarea>
          <button class="btn btn-outline-success">Send Message</button>
        </form>
      </div>
    </div>
  </div>
</template>
<style scoped>
img{
  width: 50px;
  height: 50px;
  border-radius: 50%;
}
#line{
  height: 2px;
  width: 100px;
  background: coral;
  margin-bottom: 10px;
}
span{
  display: inline-block;

}
input{
  border-color: coral;
  margin-bottom: 5px;
}
input:focus{
  border: none;
}
textarea{
  border-color: coral;
}
.btn{
  display: block;
  margin: 10px auto;
  width: 200px;

}
</style>
