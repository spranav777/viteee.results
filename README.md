




 
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
<title>VIT B.Tech.Online Counselling</title>
<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="bootstrap-3.3.7-dist/css/bootstrap.css"> 
  <script src="bootstrap-3.3.7-dist/js/jquery.min.js"></script> 
  <script src="bootstrap-3.3.7-dist/js/bootstrap.min.js"></script>
  <script src="bootstrap-3.3.7-dist/jquery-ui-1.11.4/jquery.js"></script>
  <script src="bootstrap-3.3.7-dist/jquery-ui-1.11.4/jquery-ui.js"></script> 
  <script src="bootstrap-3.3.7-dist/js/bootstrap.min.js"></script>
   <script src="bootstrap-3.3.7-dist/js/sweetalert.min.js"></script>
  <link rel="stylesheet" href="bootstrap-3.3.7-dist/css/sweetalert.css"> 
<script language="javascript">
	window.history.forward(1);
</script>

<script language="javascript">

function errorinfo()
{
	d = document.checkform;
	if(d.errormsg1.value != null)
	{
		swal(d.errormsg1.value, "", d.errormethod1.value);
		//swal(d.errormsg1.value, "", "green");
		return false;
	}
	return true;
}
</script>

<style>
  .row.content {height: 720px}
/* Style the buttons */
.btn {
  border: none;
  outline: none;
  padding: 12px 14px;
  background-color: #f1f1f1;
  cursor: pointer;
  font-size: 12px;
}

/* Style the active class, and buttons on mouse-over */
.active, .btn:hover {
  background-color: #666;
  color: white;
}
#couns-menu li{
float:left;
list-style: none;
    margin-right: 7px;
    margin-bottom: 5px;
    margin-top: 5px;
}}
#couns-menu{
margin: 16px 0;
float: left;
width: 100%;
}
#couns-menu ul{
padding:0;
}
</style>

<SCRIPT TYPE="text/javascript"> 
	function clickIE() {if (document.all) {(message);return false;}} 
	function clickNS(e) {if 
	(document.layers||(document.getElementById&&!document.all)) { 
	if (e.which==2||e.which==3) {(message);return false;}}} 
	if (document.layers) 
	{document.captureEvents(Event.MOUSEDOWN);document.onmousedown=clickNS;} 
	else{document.onmouseup=clickNS;document.oncontextmenu=clickIE;} 
	document.oncontextmenu=new Function("return false")
</SCRIPT>

<script language ="javascript">

function getPageID(x)
{
	if(x==1)
	{
		document.getElementById("pageidinfo").src = "results.jsp";
	}
	else if(x==2)
	{
		document.getElementById("pageidinfo").src = "instruction.jsp";
	}
	else if(x==3)
	{
		document.getElementById("pageidinfo").src = "payment.jsp";
	}
	else if(x==4)
	{
		document.getElementById("pageidinfo").src = "importantDates.jsp";
	}
	else if(x==5)
	{
		document.getElementById("pageidinfo").src = "choiceEntry.jsp";
	}
	else if(x==6)
	{
		document.getElementById("pageidinfo").src = "choiceEntryView.jsp";
	}
	else if(x==7)
	{
		document.getElementById("pageidinfo").src = "feesdetails.jsp";
	}
	else if(x==8)
	{
		document.getElementById("pageidinfo").src = "Contacts.jsp";
	}
	else if(x==9)
	{
		document.getElementById("pageidinfo").src = "seatAllotView.jsp";
	}
	else if(x==10)
	{
		document.getElementById("pageidinfo").src = "feedBack.jsp";
	}
	else
	{
		document.getElementById("pageidinfo").src = "default.jsp";
	}
}
</script>

</head> 
</head>


<body onload="getPageID(1);errorinfo();">



<div style="background-color:#4262a5; width:100%; float:left;">
	
<div class="col-sm-3 logo-img" style="margin-top:9px;" align="center">
	<a href="https://vit.ac.in" target="_blank"><img src="images/vitlogo.png" width="220" height="70"></a>
</div>
    
<div class="col-sm-8" style="text-align:center;">

<h2 class="header-title" style="color: #fff;font-weight: bold;font-size: 30px;margin: 15px 0 10px 0;">VIT - B.Tech. Admissions Online Counselling (2022 - 23)</h2>
</div>
</div>


<div class="container-fluid">
  <div class="row content">

	<center>
		  <div class="col-sm-12" class="progress" style="margin-bottom:-25px;">
		  <div id="couns-menu">
		   
		   <label style="margin-top:5px;"> 
			   <span><img class="image-responsive" src="view_photo.jsp?rgno=2022179383" width="70" height="80" onContextMenu="return false;" ondrag="return false;" onmousedown="return false;"/></li> 
			   </span>
			   <span style="color:#4262a5; font-size: x-large;"><font color="black"> Welcome, </font> SAI PRANAV PENCHALA <font color="green">[Application Number : 2022179383]</font></span>
		   </label>
		   <div class="col-sm-12">
			  <ul>
			  		
				    <li><b><button class="btn active" name="result" id="result" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(1)"><b>VITEEE Rank</b></button></b></li>
				    <li><b><button class="btn" name="instruction" id="instruction" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(2)"><b>Counselling Instructions</b></button></b></li>
				    <li><b><button class="btn" name="counsellingfee" id="counsellingfee" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(3)"><b>Counselling Fee</b></button></b></li>
				    <li><b><button class="btn" name="importanDate" id="importanDate" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(4)"><b>Important Dates</b></button></b></li>
				    <li><b><button class="btn" name="feesdetails" id="feesdetails" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(7)"><b>Fee Details<b></b></button></b></li>
				    <li><b><button class="btn" name="choiceEntry" id="choiceEntry" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(5)"><b>Choice Filling</b></button></b></li>
				    <li><b><button class="btn" name="viewChoices" id="viewChoices" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(6)"><b>Registered Choices</b></button></b></li>
				    <li><b><button class="btn" name="viewSeatAllotment" id="viewSeatAllotment" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(9)"><b>Seat Allotment</b></button></b></li>
				    <li><b><button class="btn" name="feedBack" id="feedBack" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(10)">Feedback</button></b></li>
				    <li><b><button class="btn" name="viewContacts" id="viewContacts" style="background-color:#4262a5; color:white; font-size: medium; font-weight: bold;" onclick="getPageID(8)"><b>Contacts</b></button></b></li>
				    
				    <li><a href="logout.jsp" class="btn btn-info btn-md" style="background-color: #800000; color: white; font-size: medium;"><span class="glyphicon glyphicon-log-out"></span> <b>Log out</b></a></li>
			   </ul>
			   </div>
		  </div>
		  </div>
	  </center>

 
   <div class="col-sm-12" align="center" style="margin-bottom:-10px;"><p align="center" style="background-color:#4262a5; color:white;"><hr style='border: 1px solid #4262a5;'></div>

	<form id="checkform" name="checkform">
    <div class="col-sm-12" align="center">
        
    
   
	 </div>
	</form>

    <div class="col-sm-12">
		<iframe height="760px" width="100%"  name="pageidinfo" id="pageidinfo" align="left" frameborder="0" >
	   	   VIT - B.Tech. Admissions Online Counselling - 2022
		   
	    </iframe>
	 </div>
    </div>         
  </div>
    
<div>
<!-- <style>
.custom-footer {
position:fixed;
background-color: #4262a5;
text-align: center;
padding:10px 0!important;
color:white;
bottom:0;
width:100%;
float:left;
}
@media screen and (max-width: 767px) {
.custom-footer {
position:inherit;
}
}
</style> -->
<footer class="custom-footer" style="background-color: #4262a5;text-align: center;padding:10px 0!important; color:white;">
 <b>
  &copy Designed and Developed by Software Development Cell, VIT, Vellore - 632 014.</b>
</footer>
</div>


</body>
</html>
