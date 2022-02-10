<template>
    <div class="container">
          
   
        <header class="d-flex flex-wrap align-items-center justify-content-right justify-content-md-between py-3  mb-4 border-bottom ">
<!--DivOne-->      
<div class="col-md-1">
    <!-- <button class="btn " type="button" data-bs-target="#f" data-bs-toggle="offcanvas" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="offcanvas">
 -->
      <img class="menu" src="../assets/menu.png" alt="" srcset=""  data-bs-target="#f" data-bs-toggle="offcanvas" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="offcanvas">
 
    
<!--offcanvas-->
<div class="offcanvas offcanvas-start  " tabindex="-1" id="f" >
	<div class="offcanvas-header ">
		<img src="../assets/ByfLnodCIAAFaFO.jpg" alt="" srcset="">
        <p>I S M A H E N</p></div>
	<div class="offcanvas-body  "> 
        <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Launch demo modal
</button>

    </div>
  </div> <!--offcanvas-->
  
<!-- Modal --> 
<div class="modal fade " id="exampleModal" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Form</h5>
      <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
          <!--form-->
         <form class="row g-3">
 
  <div class="col-md-6">
    <label for="validationEmail" class="form-label">Email</label>
    
      <input type="text" class="form-control" id="validationEmail" placeholder="email@gmaail.com" 
       required>

  </div>
  <div class="col-md-6">
    <label for="validationPassword" class="form-label">Password</label>
    <input type="Password" class="form-control" id="validationPassword" placeholder="Password" required>
  </div>
 
  
  
  <div class="col-12">
    <button class="btn btn-primary" type="submit">Submit form</button>
  </div>
</form><!--form-->
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div> <!--modal-->
</div>
<!--DivOne-->  
<!--DivTwo-->
<div class="col-md-5 text-end">
        <button type="button" class="btn btn-primary">Log-Out</button>
      </div> <!--DivTwo-->
    </header>
  </div>
    
</template>
<script>
export default{
    name:"Header"
}
</script>
<style>
.offcanvas-header{
    display: block;
}
.offcanvas-header p{
    text-align: center;
    font-size: 20px;
    color: cadetblue;
}
.offcanvas-header img{
    border-radius: 50%;
    width:70%;
    height: 70%;
   margin:0 auto auto auto;
   top: 10%;
}
.offcanvas{
    width: 20%;
}
.col-md-5 > button {
    margin: 0;
}
header{
 background-color: #7882A4
}
.menu{
    width: 40%;
}
header{
    padding: 10px;
    margin-top:-3.3%;
    margin-left: -4.6%;
    width: 62.2rem;
    position: left;
}
html{
  
    overflow-x: hidden;
}


</style>