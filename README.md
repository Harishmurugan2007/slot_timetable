# Ex03 Time Table
## Date:23.04.2025

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
<title> Course Schedule </title>
</head>
<body>
<center>
<img src="sec logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">

<caption><b>SLOT TIME TABLE - HARISH M(212224110021)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td >FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT </td>
<td>PYTHON AND LINEAR ALGEBRA</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>ENVIRONMENT SCIENCES AND SUSTAINBILITY</td>
<td> FREE SLOT</td>
<td>FUNDAMENTALS OF WEB</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >COMMUNICATIVE ENGLISH </td>
<td>FREE SLOT</td>
<td>MENTOR MEET</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
<td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>CHEMISTRY</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
<td>ENGINEERING DESIGN AND MODELLING(EDM)</td>
<td>CHEMISTRY</td>
<td>FUNDAMENTALS OF WEB</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301C</td>
<td>PYTHON AND LINEAR ALGEBRA</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CY205</td>
<td>CHEMISTRY(CHE)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI302</td>
<td>ENGINEERING DESIGN AND MODELLING(EDM)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19HS801</td>
<td>HUMAN VALUES AND PROFESSIONAL ETHICS</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![Screenshot 2025-04-23 172147](https://github.com/user-attachments/assets/9718d7de-bbaa-4da5-beb0-6b368f82f200)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
