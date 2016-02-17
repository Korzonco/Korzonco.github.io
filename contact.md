---
layout: page
title: Contact Us
permalink: /contact/
---

<head>
    <title>Example form</title>
    <style type="text/css">
    .container {
        width: 500px;
        clear: both;
    }
    .container input {
        width: 100%;
        clear: both;
    }
    .container2 {
        width: 20px;
        clear: both;
    }

    </style>
</head>

<br>
<h1 style="color:blue;"> Contact Us </h1>
Currently you are working out our page for both Dynamians and Dynamic Stores. 
However, if you want to join us or keep you updated, you can subscribe us and we 
will send you the latest update.


<!-- Simple Form https://getsimpleform.com -->
<form action="https://getsimpleform.com/messages?form_api_token=2aa27ab464ae307cb6508c36c81ed5be" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='http://localhost:4000/' />
  <!-- all your input fields here.... -->
  <table style="width:100%">
	  <col width="100px" />
	  <col width="150px" />
	  <font color="red">* Required Information</font>
	  <tr>
		<td> First Name:<font color="red">*</font> </td>
		<td> <input type='text' align="left" name='First Name: ' size="30" required/> </td>		
	  </tr>
	  <tr>
		<td> Last Name:<font color="red">*</font> </td>
		<td> <input type='text' align="right" name='Last Name: ' size="30" required/> </td>		
	  </tr>
	  <tr>
		<td> Gender: </td>
		<td> <input type="radio" name="Gender: " value="Male"> Male 
			 <input type="radio" name="Gender: " value="Female"> Female 
			 <input type="radio" name="Gender: " value="Other"> Other </td>		
	  </tr>
	  <!--
	  <tr>
		<td> Age: </td>
		<td> <input type='text' align="right" name='Age: ' size="5"/> </td>		
	  </tr>
	  -->
	  <tr>
		<td> Email:<font color="red">*</font> </td>
		<td> <input type='text' align="right" name='Email: ' size="30" required/> </td>		
	  </tr>
	  <tr>
		<td> Message: </td>
		<td> <textarea rows="4" cols="35" name="Message: " > Enter text here... </textarea> </td>		
	  </tr>
  </table>
  <input type='submit' value='Submit' />
</form>

