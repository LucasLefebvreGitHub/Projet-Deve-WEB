<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">


<style>
	.bot {
		
		display: flex;
	}

	.nav {
		background-color: white;
		z-index: 2;
		
	}





.header {
	top:50px;
	margin:-10px;
  padding: 20px;
  text-align: left;
  background: black;
  color: white;
}



.footer {
	margin:-10px;
  position: absolute;
 	bottom: 0;
  width: 100%;
  background-color: black;
  color: white;
  text-align: center;
	padding:20px;
}


</style> 


<div class="body"> 

	<div class="header">

	</div>

	<div class ="bot">



	



	<slot />
	</div>

	<div class="footer">
 	 	<a class="active" href="#"><i class="fa fa-facebook-official w3-hover-opacity"></i><a> 
		<a class="active" href="#"><i class="fa fa-instagram w3-hover-opacity"></i></a> 
		<a class="active" href="#"><i class="fa fa-linkedin w3-hover-opacity"></i></a>
	</div>

</div> 


