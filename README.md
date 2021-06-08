<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Compiled and minified CSS -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css"
    />
    <!--Import Google Icon Font-->
    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
    <!-- Font Awesome -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
      integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <title>UC3 TASK SHEET - Landing Page</title>

    <style>

      .loader_bg {
        position: fixed;
        background: rgb(230, 230, 230);
        width: 100%;
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
      }

      .loader {
        border: 5px solid;
        border-radius: 50%;
        width: 50px;
        height: 50px;
        color: cornflowerblue;
        border-top-color: transparent;
        animation: loader 1.2s linear infinite;
      }


      @keyframes loader {
     
      to {
        transform: rotate(360deg);
      }
      }
      

      .card {
        border-radius: 20px;
      }
      header {
        background: url(img/john-schnobrich-FlPc9_VocJ4-unsplash.jpg);
        background-size: cover;
        background-position: center;
        min-height: 585px;
      }
      @media screen and (max-width: 670px) {
        header {
          min-height: 500px;
        }
      } ;
    </style>
  </head>
  <body>
    
    <div class="loader_bg">
      <div class="loader">
      </div>
    </div>
    
    <!-- navbar -->
    <header>
      <nav class="nav-wrapper blue darken-1">
        <div class="container">
          <a href="index.html" class="brand-logo">Tolete.</a>
          <a
          href="#"
          class="sidenav-trigger hide-on-large-only"
          data-target="mobile-links">
          <i class="material-icons">menu</i>
        </a>
          <ul class="right hide-on-med-and-down">
            <li><a href="index.html">Home</a></li>
            <li><a href="features.html">Features</a></li>
            <li><a href="docs.html">Docs</a></li>
            <li><a href="https://www.facebook.com" class="btn-floating btn-small indigo lighten-2">
              <i class="fab fa-facebook"></i></a></li>
            <li><a href="https://www.twitter.com" class="btn-floating btn-small indigo lighten-2">
              <i class="fab fa-twitter"></i></a></li>
            <li><a href="https://www.instagram.com" class="btn-floating btn-small indigo lighten-2">
              <i class="fab fa-instagram"></i></a></li>
          </ul>
        </div>
      </nav>
      <ul class="sidenav" id="mobile-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="features.html">Features</a></li>
        <li><a href="docs.html">Docs</a></li>
      </ul>
    </header>

    <div class="container">
      <h4>Easier Deployment</h4>
      <div class="row">
        <div class="col s12 m6 l4">
          <p>
            Deploy web apps of all kinds, from large scale enterprise APIs to
            static websites for individuals. Fill out the form to try a demo of
            our platform
          </p>
          <a href="features.html" class="btn blue lighten-2 waves-effect waves-light">Read More</a>
        </div>
        

        <div class="col s12 m6 l5 offset-l7">
          <div class="form card">
            <div class="card-content">
            <h4>Request a Demo</h4>
            <form>
              <div class="form-control">
                <input type="text" name="name" placeholder="Name" required />
              </div>
              <div class="form-control">
                <input
                  type="text"
                  name="company"
                  placeholder="Company"
                  required
                />
              </div>
              <div class="form-control">
                <input type="email" name="email" placeholder="Email" required />
              </div>
              <div class="input-field center-align">
                <button class="btn blue lighten-2">Submit</button>
              </div>
            </div>
            </form>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <h4 class="center-align">Welcome to the best platform for building applications of 
        all types with modern architecture and scaling</h4>
    </div><br><br><br>


<div class="container center-align">
  <div class="row">
    <div class="col s12 m4 l4">
      <i class="fas fa-server fa-3x"></i>
      <h5>20,365,852</h5>
      <p class="text-secondary">Deployments</p>
    </div>
    <div class="col s12 m4 l4">
      <i class="fas fa-upload fa-3x"></i>
      <h5>561 TB</h5>
      <p class="text-secondary">Deployments</p>
    </div>
    <div class="col s12 m4 l4">
      <i class="fas fa-project-diagram fa-3x"></i>
      <h5>23,971,249</h5>
      <p class="text-secondary">Deployments</p>
    </div>
  </div>
</div>

 <!-- parallax -->
<div class="parallax-container">
  <div class="parallax">
<img src="/UC3 Task sheet/img/norbert-levajsics-1vwwZ-BmmrE-unsplash.jpg" alt="monitor" class="responsive-img">
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col s12 m6 l8">
      <img src="/UC3 Task Sheet/img/cli.png" alt="CLI" class="responsive-img">
    </div>
    <div class="col s12 m3 l2">
      <div class="card">
        <div class="card-content">
          <p>Easy to use, cross platform CLI</p>
        </div>
      </div>
    </div>
    <div class="col s12 m3 l2">
      <div class="card">
        <div class="card-content">
          <p>Deploy in seconds</p>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="card-panel blue lighten-2">
  <div class="container cloud">
    <div class="row">
      <div class="col s12 m6 l6">
        <h3 class="white-text">Extreme Cloud Hosting</h3>
        <p class="white-text">Cloud hosting like you’ve never seen before. Fast, effecient and scalable</p>
        <a href="features.html" class="btn blue waves-effect wave-light">Read More</a>
      </div>
      <div class="col s12 m6 l6">
      <img src="/UC3 Task Sheet/img/cloud.png" width="500px" alt="cloud">
      </div>
    </div>
  </div>
</div>

<div class="container">
  <div class="container-content">
    <h3 class="center-align">Supported Langauges</h3>
    <div class="carousel center-align">
      <a class="carousel-item" href="#one!"><img src="/UC3 Task sheet/img/logos/node.png"><h3 class="teal-text">NodeJs</h3></a>
      <a class="carousel-item" href="#two!"><img src="/UC3 Task sheet/img/logos/python.png"><h3 class="yellow-text">Python</h3></a>
      <a class="carousel-item" href="#three!"><img src="/UC3 Task sheet/img/logos/csharp.png"><h3 class="indigo-text">C#</h3></a>
      <a class="carousel-item" href="#four!"><img src="/UC3 Task sheet/img/logos/ruby.png"><h3 class="red-text">Ruby</h3></a>
      <a class="carousel-item" href="#five!"><img src="/UC3 Task sheet/img/logos/php.png"><h3 class="blue-text">PHP</h3></a>
      <a class="carousel-item" href="#six!"><img src="/UC3 Task sheet/img/logos/scala.png"><h3 class="red-text">Scala</h3></a>
      <a class="carousel-item" href="#seven!"><img src="/UC3 Task sheet/img/logos/clojure.png"><h3 class="green-text">Clojure</h3></a>
    </div>
  </div>
</div>

    <!-- Footer -->
    <footer class="page-footer blue">
      <div class="container">
        <div class="row">
          <div class="col s12 m6">
            <h5 class="white-text">Tolete.</h5>
          </div>
          <div class="col l4 offset-l2 s12">
            <ul>
              <li>
                <a class="grey-text text-lighten-3" href="index.html">Home</a>
              </li>
              <li>
                <a class="grey-text text-lighten-3" href="features.html"
                  >Features</a
                >
              </li>
              <li>
                <a class="grey-text text-lighten-3" href="docs.html">Docs</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer-copyright blue darken-4 center-align">
        <div class="container">
          <p>&copy; 2021 Tolete.</p>
        </div>
      </div>
 
    </footer>
<!-- CDNJS JQuery -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js" 
    integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ==" 
    crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <!-- Jquery -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!-- Compiled and minified JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
   
    <script>
      $(window).on("load",function(){
        $('.loader_bg').fadeOut(1000);
      })
    </script>
    <script>
      $(document).ready(function () {
        $(".sidenav").sidenav();
        $('.parallax').parallax();
        $('.carousel').carousel();
      });
    </script>
  </body>
</html>
