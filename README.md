# onkey-example1
<!DOCTYPE HTML>
<html>
<head>
<title>Javascript: onkeydown, onkeyup</title>

<style type="text/css">
	
	body 
	{
		background-color: rgb(102, 255, 255);
	}

</style>
</head>

<body>

		<input type="text" id="demo">


		<script type="text/javascript">
			console.log('javascript is working')

		function down() 
		{
			document.getElementById("demo").style.backgroundColor = "rgb(204, 0, 255)";
		}

		document.getElementById("demo").onkeydown = function()
		{
			down();
		}

		function up()
		{
			document.getElementById("demo").style.backgroundColor = "rgb(255, 102, 204)";
		}

		document.getElementById("demo").onkeyup = function()
		{
			up();
		}

	

		</script>


</body>
