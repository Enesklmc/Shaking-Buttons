"# Shaking-Buttons" 


//// Html codes 
//// issue: text in the button should be one line and not too long

<style>
	.section-1{
	background-color:#2c3e50;
	/* background-image: url("images/header-bg.jpg");
	background-repeat:no-repeat;
	background-position:center;
	color:white;
	background-size: cover;
	-moz-background-size: cover;
	-o-background-size: cover;
	-webkit-background-size: cover;
font-family: 'Open Sans', sans-serif;*/

height:120vh;
padding:15px;
}


.loading-div {
	position: fixed;
	left: 0px;
	top: 0px;
	width: 100%;
	height: 100%;
	z-index: 9999;
	background-color: #1d2731;
}

.load-gif{
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  margin: auto;
 }

 
 /* PART OF SHAKİNG BUTTONS */



#my_centered_buttons { display: flex; justify-content: center; overflow:hidden;}

/* dor older internet explorer

#my_centered_buttons_older { margin: 0 auto; width: 180px; }

*/

.btn-shake{

	border-radius:50%;
	border:2px solid #e6e6e6;
	overflow:hidden;
	float:left; 
	-moz-box-shadow:    inset 0 0 10px #000000;
	-webkit-box-shadow: inset 0 0 10px #000000;
	box-shadow:         inset 0 0 10px #000000;
	text-align: center;
	width:115px;
	height:115px;
	background-color:rgba(255,255, 255, 0.1);
	transition-duration: 0.6s;
	-webkit-transition-duration: 0.6s;
	-moz-transition-duration: 0.6s;
}

.btn-shake:hover {
	 text-decoration: none;
  animation: shake 0.3s;
  animation-iteration-count: infinite;
  background-color:rgba(0, 0, 0, 0.2);
  

}

@keyframes shake {
  0% { transform: translate(1px, 1px) rotate(0deg); }
  10% { transform: translate(-1px, -2px) rotate(-1deg); }
  20% { transform: translate(-3px, 0px) rotate(1deg); }
  30% { transform: translate(3px, 2px) rotate(0deg); }
  40% { transform: translate(1px, -1px) rotate(1deg); }
  50% { transform: translate(-1px, 2px) rotate(-1deg); }
  60% { transform: translate(-3px, 1px) rotate(0deg); }
  70% { transform: translate(3px, 1px) rotate(-1deg); }
  80% { transform: translate(-1px, -1px) rotate(1deg); }
  90% { transform: translate(1px, 2px) rotate(0deg); }
  100% { transform: translate(1px, -2px) rotate(-1deg); }
}

.but-p{
	color:white;text-align: center;
vertical-align: middle;
line-height: 110px;
font-size:11px;
font-family: 'Open Sans', sans-serif;
;   }

 /*  _____________ END OF THE  PART OF SHAKİNG BUTTONS /*

	
	</style>
<div id="my_centered_buttons">

<div class="container-fluid" style="background-color:black">  

		
 <a href="#" class="btn-shake">Greetingggg <br> asd  </a>
  <a href="#" class="btn-shake"> <p class="but-p">	Greetingggg </p>  </a>
   <a href="#" class="btn-shake"> <p class="but-p">	Greetingggg </p>  </a>
    <a href="#" class="btn-shake"> <p class="but-p">	Greetingggg  </p>  </a>
	 <a href="#" class="btn-shake"> <p class="but-p">	Greetingggg </p>  </a>
	  <a href="#" class="btn-shake"> <p class="but-p">	Greetingggg  </p>  </a>
	   <a href="#" class="btn-shake"> <p class="but-p">	Greetingggg  </p>  </a>
  

</div>

</div>
