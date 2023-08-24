# bloodbank
django-project
<!DOCTYPE html>

<html lang="en">

<head>
  <meta charset="utf-8">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.css">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

  <style type="text/css">
    .bs-example {
      margin: 0px;

    }

    .navbar-brand {
      font-size: 20px;
      font-family: sans-serif;

    }
  </style>
</head>

<body>



  <div class="bs-example">
    <nav style="background-color: #FF0018;" class="navbar navbar-expand-md navbar-dark fixed-top">
      <a href="/" class="navbar-brand"><i class="fas fa-heartbeat"></i>&nbsp; Blood Bank Management</a>
      <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-between" id="navbarCollapse">


        <div class="navbar-collapse collapse w-100 order-3 dual-collapse2">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" style="color: white;" href="/"><i class="fas fa-home"></i>&nbsp; Home</i></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" style="color: white;" href="/patient/patientlogin"><i class="fas fa-procedures"></i>&nbsp; Patient</i></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" style="color: white;" href="/donor/donorlogin"><i class="fas fa-user"></i>&nbsp; Donor</i></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" style="color: white;" href="/adminlogin"><i class="fas fa-user-shield"></i>&nbsp; Admin</i></a>
                </li>
                
            </ul>
        </div>




      </div>
    </nav>
  </div>

<!--
developed By : sumit kumar
facebook : fb.com/sumit.luv
youtube : youtube.com/lazycoders
-->
</body>

</html>
{% load static %}
<!DOCTYPE html>

<head>
    <style>
        .xyz{
          margin-bottom: 0px;
          background-image: url('{% static "image/homepage.jpg" %}');
          background-size: cover;
          background-repeat: no-repeat;
        }
      </style>
      
</head>


<body>
  {% include "blood/navbar.html" %}
<br>
<section id="section-jumbotron" style="margin-bottom: 0px;" class="jumbotron jumbotron-fluid d-flex justify-content-center align-items-center xyz">
    <div class="container text-center">
        <br><br><br><br><br><br><br><br><br><br><br><br><br><br>
     
      
      <br><br><br><br>
      
    </div>  
  </section>


  <div class="jumbotron" style="margin-top: 0px;margin-bottom: 0px;">

    <p class="lead text-center">“Opportunities knock the door sometimes, so don’t let it go and donate blood.”
      </p>
    
    <p class="text-center">- LazyCoder</p>
    
  </div>
  {% include "blood/footer.html" %}


</body>

</html>
<!--
developed By : Sonali Mishra & Vimal Kumar

-->
