<!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Dandre's Web building</title>
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
<link rel="stylesheet" href="contactform.html">
<link rel="stylesheet" 
href"https://stackpath.bootstrapcdn.com/font-
awesome/4.7.0/css/font-awesome.min.css">
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script 
src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd
/popper.min.js"></script>
<script src="url('https://photos.google.com/photo/AF1QipOQm84pciOsKg2Bywn5AtSBw4KWpFPWfl7Sz1Il')></script>
  <style>
    *
{
	margin: 0px;
	padding: 0px;
}
/*-----Navigation----*/
#nav-bar
{
	position: sticky;
	top: 0;
	z-index: 10;
}
.navbar-brand
{
	height: 40px;
	padding-left: 30px;
}
.navbar-nav li
{
	padding: 0 10px;
}
.navbar-nav li a
{
	float: right;
	text-align: left;
}
#nav-bar ul li a:hover
{
	color: #007bff!important;
}
.navbar
{
	background: #fff;
}
.navbar-toggler
{
	border: none!important;
}
.nav-link
{
	color:#555!important;
	font-weight: 600;
	font-size: 16px;
}
/*-----Slider----*/
#slider
{
	width: 100%;
}
.d-block img-fluid
{
    height= 400px;
}
/*---------About----------------*/
#about
{
    padding-top: 50px;
    padding-bottom: 50px;
    color: #555;
}
#about .btn
{
    margin-bottom: 30px;
}
.about-content
{
    padding-top: 20px;
}
.progress
{
    
    width: 50%;
}
.skills-bar p
{
    margin-bottom: 6px;
    font-weight: 600;
}
.progress-bar
{
    border-radius: 16px;
}
.progress
{
    border-radius:16px!important;
    margin-bottom: 20px;
    
}
/*------Sevices-----------*/
#services
{
    background-image: url('https://4.bp.blogspot.com/--2NmoXIwG4A/UbQw50hODTI/AAAAAAAAAV0/D_WQYfoJ75Q/s1600/The-best-top-desktop-hd-dark-black-wallpapers-dark-black-wallpaper-dark-background-dark-wallpaper-4.jpg');
    background-size: cover;
    background-position: center;
    color: #efefef!important;
    background-attachment: fixed;
    padding-top: 50px;
    padding-bottom: 10px;
}
#services h1
{
    text-align: center;
    color: #efefef!important;
    padding-bottom: 10px;
}
#services h1::after
{
    content:'';
    background: #efefef;
    display: block;
    height: 3px;
    width: 300px;
    margin: 20px auto 5px;
}
#testimonials
{
    padding-top: 50px;
    padding-bottom: 10px;
}
#testimonials h1::after
{
    content:'';
    background: #000;
    display: block;
    height: 3px;
    width: 190px;
    margin: 20px auto 5px;
}
#getintouch h1::after
{
    content:'';
    background: #000;
    display: block;
    height: 3px;
    width: 190px;
    margin: 20px auto 5px;
}
#testimonials .row
{
    margin-top: 30px;
}
.col-md-4
{
    margin: 40px auto;
}
.profile
{
    padding: 70px 10px 10px;
    background-color: #efefef;
}
.user
{
    width: 120px;
    height: 120px;
    border-radius: 60%;
}
.profile img
{
    top: -60px;
    position: absolute;
    left: calc(50% - 60px);
    border: 10px solid #fff;
}
.profile h3
{
    font-size: 20px;
    margin-top: 15px;
    color: #007bff;
}
#testimonials span
{
    font-size: 12px;
    color: #333;
}
blockquote
{
    font-size: 16px;
    line-height: 30px;
}
blockquote::before
{
    content: "''";
    font-size: 50px;
    color: #007bff;
    position: relative;
    line-height: 20px;
    bottom: -15px;
    right: 5px;
}
blockquote::after
{
    content: "''";
    font-size: 50px;
    color: #007bff;
    position: relative;
    line-height: 10px;
    bottom: -15px;
    left: 5px;
}
.profile:hover
{
    box-shadow: 0 0 15px 5px rgba(0,0,0,0.2);
    cursor: pointer;
    transition: 0.5s;
}
.try
{
    box-shadow: 0 0 15px 5px rgba(0,0,0,0.2);
    cursor: pointer;
    transition: 0.5s;
}
.kite
{
    box-shadow: 0 0 15px 5px rgba(0,0,0,0.2);
    cursor: pointer;
    transition: 0.5s;
}
/*------Get In Touch-----*/
#contact
{
    background: #efefef;
    padding-top :40px;
    padding-bottom: 40px;
    color: #777;
}
.contact-form
{
    padding: 15px;
}
.form-control
{
    border-radius: 0!important;
    border: none!important;
}
::placeholder
{
    color: #999!important;
}
.follow
{
    background: #fff;
    padding: 10px;
    margin: 15px;
}
.contact-info .fa
{
    margin: 10px;
    color: #007bff;
    font-weight: bold;
}
/*----------Footer-----------*/
#footer
{
    background: #333;
    color: #fff;
    padding: 12px
}
#color
{
    background: #efefef;
    padding: 12px;
    text-align: center;
}
  </style>
</head>
<body>
<!-----Navigation---->
<section id="nav-bar">
 <nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#"><img src="C:/Users/Adrian/Desktop/Photos/LogoMakr_2fMapj.png" width="400"  style="position: relative; right: 90px; top: -10px;"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#slider">HOME</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#about">ABOUT ME</a>
      </li>
        <li class="nav-item">
        <a class="nav-link" href="#services">SERVICES</a>
      </li>
	  <li class="nav-item">
        <a class="nav-link" href="#testimonials">TESTIMONIALS</a>
      </li>
	  <li class="nav-item">
        <a class="nav-link" href="contactform.html">CONTACT</a>
      </li>
    </ul>
  </div>
</nav>	
</section>
<!-------------------------------->
<div id="color">
<div class="main-wrap--title">
    <h1>
    "Recommended Website Builder 2020"
    </h1>
</div>
<div class="main-wrap--content">
<p>If you’re ready to create your own website but don’t know where to start, you’re in the right place. My mission is to help you build the right website for your needs.</p>    
</div>
</div>    
<!-----Slider---->
<div id="slider">
<div id="headerSlider" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#headerSlider" data-slide-to="0" class="active"></li>
    <li data-target="#headerSlider" data-slide-to="1"></li>
    <li data-target="#headerSlider" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block img-fluid" src="C:/Users/Adrian/Desktop/Photos/html-css-javascript.jpg" width="1400">
    </div>
    <div class="carousel-item">
      <img class="d-block img-fluid" width=" 1400" src="C:/Users/Adrian/Desktop/Photos/pace-oregon-state-html-css-coding-web-design.jpg">
    </div>
    <div class="carousel-item">
      <img class="d-block img-fluid" src="C:/Users/Adrian/Desktop/Photos/html-login-form.png" width="1600px" >
    </div>
  </div>
  <a class="carousel-control-prev" href="#headerSlider" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#headerSlider" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>
    <!-----About---->
<section id="about">
<div class="container">
<div class="row">
<div class="col-md-6">
<h2>About Me</h2>
<div class="about-content">
<p>Hi guys my name is D'andre Jackson I am 15
years old and my job as of right now is
to make websites. I have been making websites
since 7/17/2019 and here is the links of just a few.<br>                                   
<a href="https://successfulkid.github.io/Blog1/"  target="_blank">Blog1</a><br>                                   
<a href="https://successfulkid.github.io/Blog2/"  target="_blank">Blog2</a><br>
<a href="https://successfulkid.github.io/COVID-19/"  target="_blank">COVID-19</a></p>
<img src="C:/Users/Adrian/Desktop/Photos/banner.jpg" width="200"  style="position: relative; right: -468px; top: -160px;">
<img src="C:/Users/Adrian/Desktop/photos/banner1.jpg" width="200"  style="position: relative; right: -525px; top: -160px;">
</div>
<button type="button" class="btn btn-primary" style="position: relative; bottom: 145px;">See more>>
</button>
</div> 
<div class="col-md-6 skills-bar"></div> 
    <p style="position: relative; right: -480px; top: -200px;">Skill In Old Websites</p>
    <div class="progress" style="position: relative; right: -337px; top: -170px;">
        <div class="progress-bar" style="width: 40%;">40%</div>
    </div>
     <p style="position: relative; right: 143px; top: -125px;">Skill Level Now</p>
    <div class="progress" style="position: relative; right: -480px; top: -135px;">
        <div class="progress-bar" style="width: 85%">85%</div>
    </div>
</div>
</div>
</section>
<!-----Services------->
<section id="services">
<div class="container">
    <h1>Web Development</h1>
    <div class="row services">
        <div class="col-md-3 text-center">
            <div class="icon">
            <i class="fa fa-desktop"></i>
            </div>
            <div class="try">
            <h3 style="position: relative; right: -20px; top: -10px;">Web Pages For Models</h3>
            <p style="position: relative; right: -20px; top: -10px;">         $300        </p>
            </div>
            <div class="kite">
            <h3 style="position: relative; right: -700px; top: -125px;">Web Pages For Advertisements</h3>
            <p style="position: relative; right: -700px; top: -125px;">         $300        </p>
                <h6 style="position: relative; right: -365px;">If you want me to make a webpage for you, go to contacts, fillout the the form, and in messages tell me which one you want.</h6>
            </div>
            <!---<button type="button" class="btn btn-primary" style="position: relative; right: -825px; top: -147px;">Buy Now>>
            </button>-->
        </div>
    </div>
</div>
</section>
<!----------Testimonials--------->
<section id="testimonials">
<div class="container">
<h1 style="text-align: center">Testimonials</h1>
<p class="text-center" style="text-align: center">HERE IS WHAT SOME PEOPLE HAD TO SAY ABOUT MY WEBSITES</p>
<div class="row">
 <div class="col-md-4 text-center">
  <div class="profile">
  <img src="" class="user"> 
  <blockquote></blockquote>
      <h3><span> </span></h3>
  </div>      
 </div>
  <div class="col-md-4 text-center">
  <div class="profile">
  <img src="" class="user"> 
  <blockquote></blockquote>
      <h3><span></span></h3>
  </div>      
 </div>
  <div class="col-md-4 text-center">
  <div class="profile">
  <img src="" class="user"> 
  <blockquote></blockquote>
      <h3><span> </span></h3>
  </div>      
 </div>    
</div>
</div>
</section>
<!--------------Footer---------->
    <section id="footer">
    <div class="container text-center">
    <p>Made By Dandre Jackson</p>    
    </div>
    </section>
</body>
</html>
