# Registration-Form

<html>
<head> 
<title> Admission Form</title>
<style>body{background:linear-gradient( -120deg, rgb(118,67,199), rgb(50,150,200));color:#eeefff} 
</style>
<body>
<form><fieldset><legend><h3>Basic Detail</h3></legend><table><tr><td><div><label>
Name       <input type="text" placeholder="Name" name="name" /></label></div></tf><th>      <th/>
<div><td><label margin ="left">Father's Name   </td><td><input type="text" name="father's name" /></label></div></td><tr/></table>
<br/><label>DOB <input  type="date"  placeholder="DOB"/></label><br/>
<label>Mother's Name  <input type="text" name="mother's name" /></label>
<br/><label>Roll Number <input type="number" maxlength="6" name="roll_number" /></label>
<br/><label> Gender<label>
<input type="radio" value="Male" name="male" margin="10px"/>Male
</label><label><input type="radio" value="Male" name="male"/>Female</label>
</label><br/><label>Branch
<select name="Branch" placeholder="SELECT" value="Branch">
<option value="Electronics and Communication">ECE</option>
<option value="Computer Science and Engineering">CSE</option>
<option value="Civil Engineering">CE</option>
<option value="Information Technology">IT</option>
<option value="Mechanical Engineering">ME</option>
<option value="Integrated MSc">IMSc</option>
</select></label>
<br/>
Address 
<input type="textarea"  name="address"  size="50"/>
<br/>
Pin Code <input type="number" maxlength="6" size="10"/>
<p></p>
Mobile No <input type="number" maxlength="10" size="10"/>
</fieldset>
<fieldset>
<legend><h3>Upload Document</h3></legend>
High School Certificate<br><input type="file" name="High_School_Marksheet" /><br/>
<input type="submit" value="upload"/>
<hr/>
Intermediate Certificate<br><input type="file" name="Intermediate_Marksheet" /><br/>
<br/><input type="submit" value="upload"/>
Other Certificate<br> <input type="file" name="Other_certificate" /><br/>
<input type="submit" value="upload"/>

</fieldset>
<fieldset><legend>Academic Details</legend> <table><tr> <td> <label> Course<select value="Course" >
<option> Select</option>
<option value="BBA">BBA</option>
<option value="BCA" >BCA</option>
<option value="MBA">MBA</option>
<option value="B.Tech">BTech</option>
<option value ="BE" >BE</option></td></label>
<label>Semester
  <input type="number" maxlength="1" size="5" placeholder="sem"></label></td>





</form>
</body></html>
