# Form-of-Marathon-Race-Registration-

<!DOCTYPE html>
<html>

<head>
     <title>Form for Annual Marathon Race Registration 2022
     </title>
</head>

<body>
<h1 ><center>Annual Marathon Race Registration 2022</center></h1 >

<form action="/zerba.com">



<pre>
First Name : <input type="text" id="bsd" placeholder="First Name" name="first name"  minlength="3" maxlength="20" required >
Last Name  : <input type="text" id="mdc" placeholder="Last Name" name="Last name"  minlength="3" maxlength="20" required > <br><br>
</pre>


<label>Choose Your Gender :</label><br>

<input type="radio" name="gender" id="royal" value="Male">
<label for="royal">Male</label><br>

<input type="radio" name="gender" id="car" value="Female">
<label for="car">Female</label><br>

<input type="radio" name="gender" id="bike" value="Other">
<label for="bike">Other</label><br>

<!--Male !Female , Non-binary , I prefer not no say                                             -->


<div><p>
<lable for="kid">Select Age Group :</label>
<select name="age group" id="kid"'>

<option value="">--Select Your Age From Below--</option>
<option value="under 18">Under 18</option>
<option value="18 to 25">18 - 25</option>
<option value="25 to 40">25 - 40</option>
<option value="40 to 50">40 - 50</option>  
<option value="above 50">Above 50</option></p>
</select>
</div>


<div>
<label>Select a Race : </label>
<br>

<input type="radio" name="race" id="oggy" value="Fun Run 5KM">
<label for ="oggy">Fun Run 5KM</label><br>


<input type="radio" name="race" id="jack" value="Half Marathon">
<label for ="jack">Half Marathon</label><br>
 
<input type="radio" name="race" id="bob" value="Full Marathon">
<label for ="bob">Full Marathon</label><br>
</div>

<div><p>
<label for="olly">Email &nbsp; &nbsp; &nbsp; :   </label>
<input type="email" placeholder="Email" id="olly" name="email" required><br>

<label for="egg">Password :</label>
<input type="password" placeholder="Password" id="egg" name="password" required></p>
</div>


<input type="submit" value="Register">

</form>
</body>
</html>


  
