# Ex03 Time Table
## Date:25.03.2024

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
<img src="C:\Users\admin\OneDrive\Pictures\Screenshots\logo.png"height="100" width="600">
</center>
<br>
<table align="center" width="500" cellspacing="2" cellpadding="1" border="4" bgcolor="lightblue">
<caption><b>SLOT TIME TABLE - BALA MURUGAN S(23005271)</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cyan">Monday</th>
<th bgcolor="cyan">Tuesday</th>
<th bgcolor="cyan">Wednesday</th>
<th bgcolor="cyan">Thursday</th>
<th bgcolor="cyan">Friday</th>
<th bgcolor="cyan">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="orange">8-10</th>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
<td>Python progrmming</td>
<td>FREE SLOT</td>
<td>Computer Networks</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="orange">10-12</th>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
<td>Computer Networks</td>
<td>Creative Skills</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="orange">12-1</th>
<td colspan="7" align="center">L U N C H  B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="orange">1-3</th>
<td>Python programming</td>
<td>Physics for quantum computing</td>
<td>Physics for qauntum computing</td>
<td>Fundamentals of Web Application Development</td>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="orange">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="3">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center"><b><font color = blue>19AI414</font></b></td>
<td><b><font color = blue>Fundamentals of Web Application Development(FWAD)</font></b></td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center"><b><font color = blue>19AI301</font></b></td>
<td><b><font color = blue>Python Programming(Python)</font></b></td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center"><b><font color = blue>19CS406</font></b></td>
<td><b><font color = blue>Computer Networks(CN)</font></b></td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center"><b><font color = blue>19MA220</font></b></td>
<td><b><font color = blue>Mathematics for Artificial Intelligence(MATHS)</font></b></td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center"><b><font color = blue>19PH214</font></b></td>
<td><b><font color = blue>Physics for quantum computing(PQC)</font></b></td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center"><b><font color = blue>19EY702</font></b></td>
<td><b><font color = blue>Creative Skills</font></b></td>
</tr>
</table>
</body>
</html>
```
## OUTPUT
![image](https://github.com/bala23005271/slot/assets/155039753/78b790bd-e2d2-45f7-b419-0124ee66a465)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
