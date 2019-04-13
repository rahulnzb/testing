<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">

    <title>Hello, world!</title>
<style>
#button-addon2
{
background-color: #33cccc;
}
body
{
background-color: #99ffdd;
}
</style>
  </head>
  <body>
  
<div class="container">
  <div class="row">
   <img src="images/little.jpg">

  </div>


<div class="input-group mb-3">
  <input type="text" class="form-control" id="roll" placeholder="enter 10 digit serial number" aria-label="Recipient's username" aria-describedby="button-addon2">
  <div class="input-group-append">
    <button class="btn btn-outline-secondary" type="button" id="button-addon2" onclick="myfunction()">Search</button>
  </div>
</div>




<script>
window.alert("hello world   welcome to my world please try your luck  ");


function myfunction(){


var roll=["18011d0605","18011d0602"];

var rollnumber=document.getElementById("roll").value;

if(rollnumber=="")
{

     alert( "Please provide your 10 digit serial number!" );
     document.getElementById("phone").focus() ;
     return false;
   
}




if(rollnumber=="18011d0605"|"18011d0602")
{
alert("success");
return true;
}
else{
alert("invalid login");
return false;
}










}




</script>











</div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.6/umd/popper.min.js" integrity="sha384-wHAiFfRlMFy6i5SRaxvfOCifBUQy1xHdJ/yoi7FRNXMRBu5WHdZYu1hA6ZOblgut" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.min.js" integrity="sha384-B0UglyR+jN6CkvvICOB2joaf5I4l3gm9GU6Hc1og6Ls7i6U/mkkaduKaBhlAXv9k" crossorigin="anonymous"></script>
  </body>
</html>
