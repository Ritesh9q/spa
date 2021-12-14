<template>
<div><br>
      <router-link to="/"><button style="margin-left:5px;" class="btn btn-success" >Back</button></router-link><br>

  <div class="container">

<center>
  <div class="col-md-5">
        <div class="panel panel-primary">
            <div class="panel-heading">
               <h3 class="panel-title" align="left">
                 <span style="color:#5334DF">WAGONS</span> REGISTER
               </h3>
               <p align="left">Achieve your professional goals.</p>
            </div>
  <div class="panel-body">
    <form class = "form-signin" role = "form">
       
      <p align="left">Full Name</p><input type="email" name="text" class = "form-control" placeholder="Your Full Name" required><br>  
      <p align="left">Email Address</p><input type="email" name="email" class = "form-control" placeholder="Your Email" required><br>       
      <p align="left">Contact No<input type="number" name="contact no" class = "form-control" placeholder="Your contact number"   required><br>
     <div class="d-grid gap-2">
  <button class="btn " style="color:white;background-color:#5334DF"  type="button">Enroll Now</button>
</div>
    </form>
   </div> 
 </div>

</div>


      
</center>
</div>
</div>
</template>

<script>
export default {
    name:'Login'

}
</script>

