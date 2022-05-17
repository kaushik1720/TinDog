<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
  <!-- CSS -->
  <link rel="stylesheet" href="css/styles.css">

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
  
  <script src="https://kit.fontawesome.com/46b0410522.js" crossorigin="anonymous"></script>

  <!-- fonnts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@900&display=swap" rel="stylesheet">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
  </head>

<body>

  <section id="title" >
  <div class="container-fluide">
    <!-- Nav Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        
      <a class="navbar-brand" herf="#">TinDog</a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
         <span class="navbar-toggler-icon"></span>
      </button>
       
       <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
       <ul class="navbar-nav ms-auto">
           <li class="nav-item">
               <a class="nav-link" herf="">Home</a>
           </li>
           <li class="nav-item">
               <a class="nav-link" herf="">About</a>
           </li>
           <li class="nav-item">
               <a class="nav-link" herf="">Contact</a>
           </li>
       </ul>
       </div>
    </nav>
    <!-- Title -->

    <div class="row">
      <div class="col-lg-6 col-md-12 col-sm-12 me-auto">
        <h1>Meet new and interesting dogs nearby.</h1>
        <button class="btn btn-dark btn-lg download-btn" type="button"> <i class="fa-brands fa-apple"></i> Download</button>
        <button class="btn btn-light btn-lg download-btn" type="button"> <i class="fa-brands fa-google-play"></i> Download</button>
      </div>
    <div class="col-lg-6 col-md-12 col-sm-12 ms-auto">
      <img class="tit-img" src="images/iphone6.png" alt="iphone-mockup">
    </div>
    </div>
  </div>
  </section>


  <!-- Features -->

  <section id="features">
    <div class="container-fluide">
    <div class="row">
    <div class="col-lrg-4 col-md-4 col-sm-12">
    <i class="fa-solid fa-circle-check icon"></i>
    <h3>Easy to use.</h3>
    <p>So easy to use, even your dog could do it.</p>
    </div>
    <div class="col-lrg-4 col-md-4 col-sm-12">
      <i class="fa-solid fa-record-vinyl icon"></i>
    <h3>Elite Clientele</h3>
    <p>We have all the dogs, the greatest dogs.</p>
    </div>
    <div class="col-lrg-4 col-md-4 col-sm-12">
      <i class="fa-solid fa-heart icon"></i>
    <h3>Guaranteed to work.</h3>
    <p>Find the love of your dog's life or your money back.</p>
    </div>
    </div>
    </div>
  </section>

<!-- carousel -->
  
  
<!-- Testimonials -->
  <section id="testimonials">
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="false">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2>I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonials-img" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
      </div>
      <div class="carousel-item">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonials-img" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleSlidesOnly" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleSlidesOnly" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>
      </button>
    </div>

  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-img" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-img" src="images/tnw.png" alt="tnw-logo">
    <img class="press-img" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-img" src="images/mashable.png" alt="mashable-logo">
  </section>






  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>


    <div class="row">
      <div class="  pricing-col col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Chihuahua</h3>
          </div>
          <div class="card-body">
            <h2>Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <div class="d-grid gap-2">
            <button  class="btn btn-lg btn-block btn-outline-dark btn-padding" type="button">Sign Up</button>
            </div>
          </div>
        </div>
      </div>

      <div class=" pricing-col col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Labrador</h3>
          </div>
          <div class="card-body">
            <h2>$49 / mo</h2>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <div class="d-grid gap-2">
              <button  class="btn btn-dark btn-lg btn-block" type="button">Sign Up</button>
            </div>
            </div>
        </div>
      </div>

      <div class=" pricing-col col-lg-4">
        <div class="card">
          <div class="card-header">
            <h3>Mastiff</h3>
          </div>
          <div class="card-body">
            <h2>$99 / mo</h2>
            <p>Pirority Listing</p>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <div class="d-grid gap-2">
              <button  class="btn btn-dark btn-lg btn-block" type="button">Sign Up</button>
            </div>
            </div>
        </div>
      </div>
    </div>
 </section>


  <!-- Call to Action -->

  <section id="cta">
    <div class="container-fluide">
      <div class="col-lg-12 col-md-12">
        <h3>Find the True Love of Your Dog's Life Today.</h3>
      </div>
      <div class="col-lg-12 col-md-12">
        <button class="btn btn-md btn-light" type="button"> <i class="fa-brands fa-google-play"></i> Download</button>
        <button class="btn btn-md btn-dark" type="button"> <i class="fa-brands fa-apple"></i> Download</button>
      </div>
    </div>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <p>© Copyright 2018 TinDog</p>

  </footer>


</body>

</html>
