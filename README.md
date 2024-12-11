<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Portfolio</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
    <style> 
      .box {
        width: 100px;
        height: 100px;
        background-color: red;
        position: relative;
        animation-name: example;
        animation-duration: 4s;
        animation-iteration-count: infinite;
      }
      
      @keyframes example {
        0%   {background-color:red; left:-25px; top:-276px;}
        25%  {background-color:yellow; left:1400px; top:-276px;}
        50%  {background-color:blue; left:1400px; top:0px;}
        75%  {background-color:green; left:-25px; top:0px;}
        100% {background-color:red; left:-25px; top:-276px;}
      }
      </style>
  </head>
  <body>
    <!-- Navigation Bar -->
    <div style="background-color: seashell; border-bottom-style: ridge;">
    <header class="d-flex justify-content-center py-3">
      <ul class="nav nav-pills">
        <li class="nav-item">
          <a href="#" class="nav-link active" aria-current="page">About me</a>
        </li>
        <li class="nav-item"><a href="Example1.html" class="nav-link">Project 1</a></li>
        <li class="nav-item"><a href="Example2.html" class="nav-link">Project 2</a></li>
        <li class="nav-item"><a href="Example3.html" class="nav-link">Project 3</a></li>
        <li class="nav-item"><a href="Contact.html" class="nav-link">Contact</a></li>
      </ul>
    </header>
   </div>
    <div class="px-4 pt-5 my-5 text-center border-bottom">
      <h1 class="display-4 fw-bold text-body-emphasis">Things about me</h1>
      <div class="col-lg-6 mx-auto">
        <p class="lead mb-4">
             My name is Alfredo, Im here to learn more about html,css and now Java.
        </p>
      <div class="overflow-hidden" style="max-height: 30vh">
        <div class="container px-5">        </div>
      </div>
    </div>
    <div class="box">  <img
      src="Images/Screenshot 2024-12-11 083628.png" style="width: 100px; height: 100px;" </div>
  </body>
</html>
https://alfredo-l0n.github.io/Portfolio.html
