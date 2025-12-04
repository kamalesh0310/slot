# Ex03 Time Table
## Date:28.11.2025
Ref no: 25018201

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
~~~
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="3" bgcolor="maroon">
<caption><b>SLOT TIME TABLE - Kamalesh.E (25018201 )</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="blue">Monday</th>
<th bgcolor="blue">Tuesday</th>
<th bgcolor="lime">Wednesday</th>
<th bgcolor="navy">Thursday</th>
<th bgcolor="olive">Friday</th>
</tr>
<tr align="center">
<th bgcolor="red">8–10</th>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>PUBLIC SPEAKING</td>
<td>PYTHON PROGRAMMING</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td>PUBLIC SPEAKING</td>
</tr>
<tr>
<th bgcolor="aqua">12-1</th>
<td colspan="5" align="center">LUNCH</td>
</tr>
<tr align="center">
<th bgcolor="teal">1-3</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>SOFT SKILLS</td>
</tr>
<tr align="center">
<th bgcolor="gray">3-5</th>
<td>PUBLIC SPEAKING</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>PHYSICS FOR QUANTUM COMPUTATION</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="1">
<tr align="center">
<th>S. No.</th>
<th>Course Code</th>
<th>Course Name</th>
</tr>
<tr>
<td align="center">1</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2</td>
<td align="center">19AI301</td>
<td>PYTHON PROGRAMMING(PYTHON PROGRAM)</td>
</tr>
<tr>
<td align="center">3</td>
<td align="center">19EN105</td>
<td>Public speaking (ps)</td>
</tr>
<tr>
<td align="center">4</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
~~~
## OUTPUT
<img width="1899" height="910" alt="Screenshot 2025-12-04 122327" src="https://github.com/user-attachments/assets/2949359b-bfd9-4ac2-9d67-18de8b4ebc55" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
