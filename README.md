<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="footer.css">
<link rel="stylesheet" href="css/global_Definer.css">
<!-- Navigation -->
	<style> 
body {
  margin: 0;
  background-image: linear-gradient( 109.6deg, rgba(156,252,248,1) 11.2%, rgba(110,123,251,1) 91.1% );
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {

  background-color: #333;
  position: fixed;

  width: 100%;
}

.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #04AA6D;
  color: white;
}



@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}
</style>
<!--End of Navigation -->
<!--Slider-->
<style>
	* {box-sizing: border-box}
	body {font-family: Verdana, sans-serif; margin:0}
	.mySlides {display: none}
	img {vertical-align: middle;}
	
	/* Slideshow container */
	.slideshow-container {
	  max-width: 10000px;

	  position: relative;
	}
	
	/* Next & previous buttons */
	.prev, .next {
	  cursor: pointer;
	  position: absolute;
	  top: 50%;
	  width: auto;
	  padding: 16px;
	  margin-top: -22px;
	  color: white;
	  font-weight: bold;
	  font-size: 18px;
	  transition: 0.6s ease;
	  border-radius: 0 3px 3px 0;
	  user-select: none;
	}
	
	/* Position the "next button" to the right */
	.next {
	  right: 0;
	  border-radius: 3px 0 0 3px;
	}
	
	/* On hover, add a black background color with a little bit see-through */
	.prev:hover, .next:hover {
	  background-color: rgba(0,0,0,0.8);
	}
	
	/* Caption text */
	.text {
	  color: #f2f2f2;
	  font-size: 30px;
	  padding: 8px 12px;
	  position: absolute;
	  top: 200px;
	  width: 100%;
	  text-align: center;
	  font-family: 'Poppins',Helvetica,Arial,Lucida,sans-serif !important;
    	letter-spacing: -1px !important;
	line-height: 1.3em !important;
	}
	

/* CSS */
.button-54 {
  font-family: "Open Sans", sans-serif;
  font-size: 16px;
  letter-spacing: 2px;
  text-decoration: none;
  text-transform: uppercase;
  color: green;
  cursor: pointer;
  border: 3px solid;
  padding: 0.25em 0.5em;
  box-shadow: 1px 1px 0px 0px, 2px 2px 0px 0px, 3px 3px 0px 0px, 4px 4px 0px 0px, 5px 5px 0px 0px;
  position: absolute;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  top: 35%;
  text-align: center;
  left: 40%;

  
}

.button-54:active {
  box-shadow: 0px 0px 0px 0px;

}

@media (min-width: 768px) {
  .button-54 {
    padding: 0.25em 0.75em;
  }
}
	.btn{
	  top: 400px;
	  width: 100%;
	  position: absolute;
	  text-align: center;
	  color: blue;
	}
	
	/* Number text (1/3 etc) */
	.numbertext {
	  color: #f2f2f2;
	  font-size: 12px;
	  padding: 8px 12px;
	  position: absolute;
	  top: 0;
	}
	
	/* The dots/bullets/indicators */
	.dot {
	  cursor: pointer;
	  height: 15px;
	  width: 15px;
	  margin: 0 2px;
	  background-color: #bbb;
	  border-radius: 50%;
	  display: inline-block;
	  transition: background-color 0.6s ease;
	}
	
	.active, .dot:hover {
	  background-color: #717171;
	}
	
	/* Fading animation */
	.fade {
	  animation-name: fade;
	  animation-duration: 1.5s;
	}
	
	@keyframes fade {
	  from {opacity: .4} 
	  to {opacity: 1}
	}
	
	/* On smaller screens, decrease text size */
	@media only screen and (max-width: 300px) {
	  .prev, .next,.text {font-size: 11px}
	}
	</style>
	<!--End of Slider-->
	<style>
		.wrapper {
    display: flex;
    position: relative;
}
</style>

	<style>
		* {
		  box-sizing: border-box;
		}
		
		
		.header {
		  text-align: center;
		  padding: 32px;
		}
		
		.row {
		  display: -ms-flexbox; /* IE 10 */
		  display: flex;
		  -ms-flex-wrap: wrap; /* IE 10 */
		  flex-wrap: wrap;
		  padding: 0 4px;
		}
		
		/* Create two equal columns that sits next to each other */
		.column {
		  -ms-flex: 50%; /* IE 10 */
		  flex: 50%;
		  padding: 0 4px;
		}
		
		.column img {
		  margin-top: 8px;
		  vertical-align: middle;
		}
		.nice{
			background-color: limegreen;
			color : blue;
			width: 90px;

		}
</style>		
</head>
<body>

<div class="topnav" id="myTopnav">
	<a href="#home" class="active">Executive Furnitures</a>
  <a href="#home" >Home</a>
  <a href="#shop">Shop</a>
  <a href="#about">About Us</a>
  <a href="#contact">Contacts</a>
  

  </a>
</div>
<div class="slideshow-container" id="home">

	<div class="mySlides fade">
	
	  <img  src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg" style="width:100%">
	  <div style="top : 10%"><h2 style="text-align: center;">Shop Our Best Couches</h2><h3 style="text-align: center;">Browse through our catalogue of homely couches</h3>
			</div>
		<button class="button-54" role="button" href = "shop">Shop Now</button>

		
	
	</div>
	
	<div class="mySlides fade">
	  
	  <img src="https://yeebo.co.za/wp-content/uploads/2022/07/Furniture-at-yeebo.co_.za_.jpeg" style="width:100%">
	  <div ><h2>Shop Our Best Couches</h2>Browse through our catalogue of homely couches
		shop now
		</div>
		<button class="button-54" role="button" href = "shop">Shop Now</button>

	</div>

	</div>
	
	<div class="mySlides fade">
	 
	  <img src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg"  style="width:100%">
	  <div><h2>Shop Our Best Couches</h2>Browse through our catalogue of homely couches
		shop now
		</div>
		<button class="button-54" role="button" href = "shop">Shop Now</button>

	</div>

</div>
	</div>
	
	<a class="prev" onclick="plusSlides(-1)">❮</a>
	<a class="next" onclick="plusSlides(1)">❯</a>
	
	</div>
	<br>
	
	<div style="text-align:center">
	  <span class="dot" onclick="currentSlide(1)"></span> 
	  <span class="dot" onclick="currentSlide(2)"></span> 
	  <span class="dot" onclick="currentSlide(3)"></span> 
	</div>
	<div id="about">
	<h1 style="text-align: center;">About Us</h1>
	<p style="text-align: center;">Executive Furnitures was founded by Mr. L Majola in the year of 2010,
Executive Furnitures specialises in home, shops and industrial furniture. Our company  offers long and short term services and
		  we proud of serving South African communities, which goes back over the years. </p>
		</div>
	<div style="text-align: center;" id="shop">
		Our products
	</div>
	  <div class="row"> 
		<div class="column">
		  <img src="https://yeebo.co.za/wp-content/uploads/2022/07/Furniture-at-yeebo.co_.za_.jpeg" style="width:100%">
		  
		  <div style="text-align: center;">
						
						<button class="nice" ><a href="https://api.whatsapp.com/send?phone=+27631241960&text=Is this available?">Whatsapp Chat</a></button>
					</div>

					</div>
		<div class="column">
		  <img src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg" style="width:100%">
		 
		  <div style="text-align: center;">
			
						<button class="nice" ><a href="https://api.whatsapp.com/send?phone=+27631241960&text=Is this available?">Whatsapp Chat</a></button>
		</div>
		 
		</div>  
		<div class="column">
			<img src="https://yeebo.co.za/wp-content/uploads/2022/07/Furniture-at-yeebo.co_.za_.jpeg" style="width:100%">
			
			<div style="text-align: center;">
				<button class="nice" ><a href="https://api.whatsapp.com/send?phone=+27631241960&text=Is this available?">Whatsapp Chat</a></button>
			</div>
		  
		
		</div>
		<div class="column">
			<img src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg" style="width:100%">
				<div style="text-align: center;">
				<button class="nice" ><a href="https://api.whatsapp.com/send?phone=+27631241960&text=Is this available?">Whatsapp Chat</a></button>
			</div>
		   
		</div>
		<div class="column">
			<img src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg" style="width:100%">
				<div style="text-align: center;">
				
						<button class="nice" ><a href="https://api.whatsapp.com/send?phone=+27631241960&text=Is this available?">Whatsapp Chat</a></button>
			</div>
		   
		</div>
		<div class="column">
			<img src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg" style="width:100%">
				<div style="text-align: center;">
				<button class="nice" >Buy now</button>
			</div>
		   
		</div>
		<div class="column">
			<img src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg" style="width:100%">
				<div style="text-align: center;">
				
						<button class="nice" ><a href="https://api.whatsapp.com/send?phone=+27631241960&text=Is this available?">Whatsapp Chat</a></button>
			</div>
		   
		</div>
		<div class="column">
			<img src="https://yeebo.co.za/wp-content/uploads/2022/07/Enjoy-sleeping-again-with-yeebo.co_.za_.jpeg" style="width:100%">
				<div style="text-align: center;">
				
						<button class="nice" ><a href="https://api.whatsapp.com/send?phone=+27631241960&text=Is this available?">Whatsapp Chat</a></button>
			</div>
		   
		</div>
	  </div>
	  

	<script>
		let slideIndex = 1;
		showSlides(slideIndex);
		
		function plusSlides(n) {
		  showSlides(slideIndex += n);
		}
		
		function currentSlide(n) {
		  showSlides(slideIndex = n);
		}
		
		function showSlides(n) {
		  let i;
		  let slides = document.getElementsByClassName("mySlides");
		  let dots = document.getElementsByClassName("dot");
		  if (n > slides.length) {slideIndex = 1}    
		  if (n < 1) {slideIndex = slides.length}
		  for (i = 0; i < slides.length; i++) {
			slides[i].style.display = "none";  
		  }
		  for (i = 0; i < dots.length; i++) {
			dots[i].className = dots[i].className.replace(" active", "");
		  }
		  slides[slideIndex-1].style.display = "block";  
		  dots[slideIndex-1].className += " active";
		}
		</script>
		
<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>
<footer class="footer" id="contact">
	<div class="footer-left">
		<img src="https://yeebo.co.za/wp-content/uploads/2022/07/Furniture-at-yeebo.co_.za_.jpeg" style="width:70%">
		  
		<!--div class="social-media">
			<a href="bt"><i class="fa fa-facebook">Facebook</i></a>
			<a href="bp"><i class="fa fa-twitter">Tweeter</i></a>
			<a href="bg"><i class="fa fa-whatsapp">WhatsApp</i></a>
			<a href="g"><i class="fa fa-linkedin">Linkedin</i></a>
		</div-->
	</div>
	
	<ul class="footer-right">
		<li>
			<h2>Services</h2>
	
			<ul class="box">
				<li>Automen</li>
				<li>Headboard</li>
			
				<li>Wardrobe</li>
				<li>Sofas</li>
				<li>Chest of Drawers</li>
				
			</ul>
		</li>
	
			<li>
				<h2>Address</h2>
	
			<ul class="box">
				<li>Johannesburg</li>
				
			</ul>
		</li>
			<li>
				<h2>Contact us</h2>
	
			<ul class="box">
				<li>Contact person: Liberty</li>
				<li>Cell: 0631241960</li>
				<li>Email us at: libertycoolmansion@gmail.com</li>
			</ul>
		</li>
	</ul>

	<div class="mps-lf-bottom-footer-docxs">
		<div class="mps-lf-bottom-footer-links">
			
			<!--a href="cooi" class="mps-lf-bottom-footer-linker">Privacy Policy </a> |
			<a href="cooi" class="mps-lf-bottom-footer-linker">Terms of Use </a-->
		</div>
	
	<div class="footer-bottom">
		 &copy; 2022 Executive Furnitures. All rights reserved.
	</div>
	</footer>


</body>
</html>
