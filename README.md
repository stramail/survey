# survey
<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>Untitled Document</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
 <!-- <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>-->
</head>
<style>
.f {
	display:none;	
}
#su {
	display:block;
	}
#tos {
	display:none;
	}
</style>
<body>
<a href="#page=1">


</a>
<a href="surveyIntake.php">TAKE A SURVEY</a>

<div class="row">
<h1>Ask a Survey</h1>
  <div class="hit"></div>
</div>
<div class="row">
  <div class="col"></div>
  
</div>
<div class="row">


</div>
<script>
$(document).ready(function(){
	/**/
		
		var o=$("#oh").click(function(){
		var h=$("#gt").val();
		
		if(h.length!="") {
			var y=$("#one").val();
			
			
			
				/*var so=$(".col").val();*/
			$(".col").empty();
			var gog=$(".col").append(h);
			var uh= "ko="+gog;
			good(h);
			$("#gt").val("");
			$(".f").css("display", "block");
			$("#su").css(display,none);		}
    });
	});
	
</script>

<form>
<div id="su">
<p>Ask a question.</p>
<input type="text"size="34"id="gt"placeholder="What is your survey question?">

<input type="button" id="oh" value="submit">
<br/>
</div>
<div id="tos">
<input type="button" onclick="tim()" id="lk"value="NEXT">
</div>
</form>
<script>alert
function tim(h) {
			window.location.href="surveyIntake.php/?m="+h;
			alert('this where im');
			}
function good(h) {
			if(h!=null){
			
			document.getElementById("su").style.display="none";
			document.getElementById("tos").style.display="block";
			
			
			}}
			
			
</script>
<label>Question</label>
			<input type="radio" >
</body>
</html>
