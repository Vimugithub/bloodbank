# bloodbank
django-project
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
