"# Shaking-Buttons" 


//// Html and css codes 
//// issue: text in the button should be one line

## Html Codes
```

<div id="my_centered_buttons">
  <div class="container-fluid">  

	<a href="#" class="btn-shake"> <p class="but-p"> Greetingggg< /p>   </a>
  <a href="#" class="btn-shake"> <p class="but-p">	Contact us </p>  </a>
  <a href="#" class="btn-shake"> <p class="but-p">	Greetingggg</p>  </a>
	<a href="#" class="btn-shake"> <p class="but-p">	Greetingggg</p>  </a>
	<a href="#" class="btn-shake"> <p class="but-p">	Greetingggg</p>  </a>
	<a href="#" class="btn-shake"> <p class="but-p">	Greetingggg</p> </a>
  
  </div>
</div>
```

## Css codes
```




#my_centered_buttons { display: flex; justify-content: center; overflow:hidden;}

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
font-size:14px;
font-family: 'Open Sans', sans-serif;
;   }


```
