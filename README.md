<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width">
	<title>SHAPEAI</title>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x"
	 crossorigin="anonymous">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
	<! -- Navbar -->
	<nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-primary">
		<div class="container-fluid">
			<a class="navbar-brand" href="#">SHAPEAI</a>
			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon "></span>
      </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#hero">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#skills">Our Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#works">Our Works</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#Contact">Contact US</a>
        </li>
      </ul>
    </div>
    </div>
  </nav>
<main class="container mt-3">
  <section id="hero" class="d-flex justify-content-sm-center justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row">
	<! -- Hero -->
  <div class="d-flex justify-content-sm-center align-items-center flex-column justify-content-sm-start align-items-md-start">
    <h5>Hii!</h5>
    <h1>I'M ShapeAI Student</h1>
    <p>A Webdevelpors Community!</p>
    <p>Here is My Instructor 👉🏼</p>
    <a href="https://www.shapeai.tech/" class="btn btn-primary">ShapeAI WebSite</a>
  </div>

  <div class="w-25 w-25"><img src="https://uploads-ssl.webflow.com/60798d9b0b61160814b3d8c3/60943131bc72bf3f15aafbca_131043066_1651639488351047_6499827813703794081_n.jpg" alt="image" class="w-100 h-100 rounded-circle shadow">
  </div>
  <div class="d-none d-md-block w-25 h-25"></div>
  </section>
  <section id="skills"class="mt-5 p-4">
	<! -- Our Skills -->
  <h1 class="text-primary text-center">Our Skill Set</h1>
  <div class="mt-4 p-4 d-md-none d-flex justify-content-evenly">
    <i class="fab fa-html5 fa-7x"style="color:#f4470b;"></i>
    <i class="fab fa-css3-alt fa-7x text-primary"></i>
    <i class="fab fa-bootstrap fa-7x" style="color:#730fef;"></i>
  </div>
  <div class="mt-4 p-4 d-none d-md-flex justify-content-evenly">
    <i class="fab fa-html5 fa-7x"style="color:#f4470b;"></i>
    <i class="fab fa-css3-alt fa-7x text-primary"></i>
    <i class="fab fa-bootstrap fa-7x" style="color:#730fef;"></i>
  </div>
  </section>
  <section id="works" class="mt-4 p-4">
	<! -- Our Works -->
  <h1 class="text-primary text-center">Internship Programs</h1>
  <div class="d-flex flex-column flex-md-row justify-content-md-evenly gap-3">
  <div class="card mt-3 mb-2">
  <img src="https://uploads-ssl.webflow.com/60798d9b0b61160814b3d8c3/6092992cda3e5661a02237dd_iStock_71952335_LARGE-1024x683.jpg" class="card-img-top" alt="img">
  <div class="card-body">
    <h5 class="card-title">Webdev</h5>
    <p class="card-text">Join us for the 2.5 month-long intensive industrial training and internship. Get placed as a Full-Stack Web Developer or a Software Development Engineer in your Dream Company</p>
    <a href="https://pages.razorpay.com/pl_H7eMUbPYxNWf11/view" class="btn btn-primary">Enroll Now</a>
  </div>
  </div>
  <div class="card mt-3 mb-3">
  <img src="https://uploads-ssl.webflow.com/60798d9b0b61160814b3d8c3/6092edeb5899b292dbcda406_1*QSDBne0uwCD7chzSt6EvKQ.jpeg" class="card-img-top" alt="img">
  <div class="card-body">
    <h5 class="card-title">Data Analyst And Training And Internship</h5>
    <p class="card-text">Join us for the 2.5 month-long intensive industrial training and internship. Get placed as a Data Analyst or a Software Development Engineer in your Dream Company</p>
    <a href="https://pages.razorpay.com/pl_H7eOCqNWS33X6i/view" class="btn btn-primary">Enroll Now</a>
  </div>
  </div>
</div>
  </section>
  <section id="Contact" class="mt-4 py-4">
	<! -- Contact US -->
  <h1 class="text-primary text-center">Contact Form</h1>
  <div class="row">
    <div class="col-sm col-md-8">
  <form>
    <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
</div>
<div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">Your Message</label>
  <textarea class="form-control" id="exampleFormControlTextarea1" required placeholder="enter your amazing message!" rows="3"></textarea>
</div>
<button type="Submit" class="btn btn-primary">Submit</button>
  </form> 
</div>
<div class="col-sm col-md-4">

  <div class="mt-3">
      <h4><i class="fas fa-at"></i>manishjon1065@gmail.com</h4>
      <button type="button" class="btn btn-outline-primary">
      
        <a href="https://github.com/ShapeAI"><i class="fab fa-github"></i></a>
      </button>

  </div>
  </section>
</main>
</body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

</html>
