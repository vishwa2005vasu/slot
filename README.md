# Ex03 Time Table
## Date:13/3/2024
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
     <title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width"550">
</center>
<br>
     <table align="center" width="550" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
     <caption><b>Time Table</b></caption>
<tr align="center">
	<th bgcolor="red">Day/Time</th>
	<th bgcolor="red">Monday</th>
	<th bgcolor="red">Tuesday</th>
	<th bgcolor="red">Wednesday</th>
	<th bgcolor="red">Thursday</th>
 	<th bgcolor="red">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="blue">8-10</th>
	<td>Maths</td>
	<td>BEEE</td>
	<td>FWAD</td>
	<td >Free Slot</td>
    <td>BEEE</td>
</tr>
<tr align="center">
	<th bgcolor="blue">10-12</th>
	<td>FREE SLOT</td>
	<td>FWAD</td>
	<td>DBMS</td>
    <td>COMPILER DESIGN</td>
    <td>FREE SLOT</td>

</tr>
<tr>
	<th bgcolor="blue">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="blue">1-3</th>
	<td>FWAD</td>
	<td>DBMS</td>
	<td>C</td>
    <td>MATHS</td>
    <td>FREE SLOT</td>

</tr>
<tr align="center">
	<th bgcolor="blue">3-5</th>
	<td colspan="3">FREE SLOT</td>
	<td>FREE SLOT</td>
    <td>FREE SLOT</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19MA218</td>
<td>MATHS</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Fundamentals Of Web Application Development</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS404</td>
<td>Database Management System and Its Application</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE305</td>
<td>BASIC ELECTICAL,ELECTRONICS AND MEASURMENT ENGINEERING </td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS409</td>
<td>COMPILER DESIGND</td>
</tr>
<tr>
    <td align="center">6.</td>
    <td align="center">19CS302</td>
    <td>C PROGRAMMING </td>
    </tr>
</table>
</body>
</html>
```

## OUTPUT

![vs,](https://github.com/vishwa2005vasu/slot/assets/135954202/041dcc68-b0b1-4a41-9211-5c89981a09f1)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
