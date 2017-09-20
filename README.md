# css-animation : Image or Div Rotation.

HTML File: index.html
<div class="image-rotation">
	<div class="image-rotation1">
	  <p>Transform</p>
	</div>
</div>


CSS File: style.css

.image-rotation{
	background:red;
	height:300px;
	width:300px;
	margin:auto;
	margin-top:150px;
	transform: rotateZ(-45deg);
}
.image-rotation1{
	background:green;
	height:300px;
	width:214px;
	margin:auto;
	margin-top:150px;
	transform: rotateX(-45deg);
	
}
.image-rotation1 p{
	font-size:44px;
	transform: rotateZ(180deg);
	margin-left:14px;
}
.image-rotation:hover{
	transform: rotateZ(-40deg);
}



