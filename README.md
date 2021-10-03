# Parnaoz1
My Portfolio
<!DOCTYPE html>
<html>
<head>
	<title>Parnaoz1</title>
	<style> 
body { 
  background:url("background1.jpg");
  background-repeat: 5;
  background-size:100%;

color:orange;
}
h1 {
    color:darkorange;
}
h2 {
    color: darkorange;
}

</style>
</head>
<body>
    <header>
        <nav>


        </nav>

    </header>
    <main>
<h1 style="text-align:center;"> Parnaoz Sonishvili </h1>
<p style="text-align: center;">Graphic Designer & Web Developer </p>
<button style="margin:10px 170px">About me</button>              <button style="margin:10px 170px">Designs</button>              <button  style="margin:10px 170px">Contact</button>
<hr>
<h1 style="text-align: center;">About Me </h1>
<img src="fako.jpg" Alt="Parnaoz" height="400" width="240" style="vertical-align:middle;margin:0px 250px; border:5px solid black">
<img src="fako1.jpg" Alt="Parnaoz"height="400" width="240" style="vertical-align:middle;margin:0px 0px; border:5px solid black">
<p style="text-align: center;">Hello, I am Parnaoz Sonishvili 17 years old from Georgia.I am Graphic Designer with 2 years of experience and begginer Web Developer. </p>
<p style="text-align: center;">I have created many Logos, Designs and Graphic Arts. </p>
</main>
<footer>
<h2 style="text-align: center;"> My Designs </h2>
<h3 style="text-align: center;"> Logos </h3>
<img src="logo.png" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="logo6.jpg" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="logo2.jpg" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="logo3.jpg" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="logo8.jpg" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="logo5.png" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 45px; border:5px solid black">
<img src="logo1.png" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 45px; border:5px solid black">
<img src="logo7.jpg" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 45px; border:5px solid black">
<img src="logo4.png" alt="Logo" width="200" height="200" style="vertical-align:middle;margin:50px 45px; border:5px solid black">
<h3 style="text-align: center;"> Designs </h3>
<img src="design.png" alt="Design" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="design1.png" alt="Design" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="design5.png" alt="Design" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="design4.jpg" alt="Design" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<img src="design3.png" alt="Design" width="200" height="200" style="vertical-align:middle;margin:50px 15px; border:5px solid black">
<h3 style="text-align: center;">Graphic Arts </h3>
<img src="art.jpg" alt="Art" width="360" height="200" style="vertical-align:middle;margin:50px 120px; border:5px solid black">
<img src="art1.jpg" alt="Art" width="360" height="200" style="vertical-align:middle;margin:50px 120px; border:5px solid black">
<hr>
</footer>
<h1 style="text-align:left">Contact Me</h1>

<form action="//submit.form" id="ContactUs100" method="post" onsubmit="return ValidateForm(this);">
<script type="text/javascript">
function ValidateForm(frm) {
if (frm.Name.value == "") { alert('Name is required.'); frm.Name.focus(); return false; }
if (frm.FromEmailAddress.value == "") { alert('Email address is required.'); frm.FromEmailAddress.focus(); return false; }
if (frm.FromEmailAddress.value.indexOf("@") < 1 || frm.FromEmailAddress.value.indexOf(".") < 1) { alert('Please enter a valid email address.'); frm.FromEmailAddress.focus(); return false; }
if (frm.Comments.value == "") { alert('Please enter comments or questions.'); frm.Comments.focus(); return false; }
return true; }
</script>
<table style="width:100%;max-width:550px;border:0;" cellpadding="8" cellspacing="0">
<tr> <td>
<label for="Name" style="text-align: center;"> Full Name*:</label>
</td> <td>
<input name="Name" type="text" maxlength="60" style="width:100%;max-width:250px;" />
</td> </tr> <tr> <td>
<label for="PhoneNumber">Phone number:</label>
</td> <td>
<input name="PhoneNumber" type="text" maxlength="43" style="width:100%;max-width:250px;" />
</td> </tr> <tr> <td>
<label for="FromEmailAddress">Email address*:</label>
</td> <td>
<input name="FromEmailAddress" type="text" maxlength="90" style="width:100%;max-width:250px;" />
</td> </tr> <tr> <td>
<label for="Comments">Comments*:</label>
</td> <td>
<textarea name="Comments" rows="7" cols="40" style="width:100%;max-width:350px;"></textarea>
</td> </tr> <tr> <td>
* - required fields
</td> <td>

<input name="skip_Submit" type="submit" value="Submit" />

</table>
</form>
</body>
</html>
