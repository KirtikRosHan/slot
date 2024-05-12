# Ex03 Time Table
## Date:14.03.2024

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
<title> TIME TABLE </title>   
</head>
<body>
<center>
<img src="/static/logo.png"height="100"width="540">
</center>
<br>
<table align="center" width="1000" border="5" bgcolor="Lavender" cellspacing="12" cellpadding="12">
<caption><b>SLOT TIME TABLE - Kirtik Roshan(212221043002)</b></caption>

<tr bgcolor="indigo">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>
<tr align="center">
   <th bgcolor="tan"> 8-10 </th>
   <td bgcolor="red"><b> Fundamentals Of Web Development Application</b></td>
   <td> Free Slot </td>
   <td bgcolor="cyan"><b>Problem sloving And Python Programming</b></td>
   <td> Free Slot </td>
   <td> Free Slot </td>
   <td> Free Slot </td>
</tr>
<tr align="center">
    <th bgcolor="tan"> 10-12 </th>
    <td> Free Slot</td>
    <td bgcolor="olive"><b>Parallel Computing Architecture</b></td>
    <td bgcolor="olive"><b>Parallel Computing Architecture</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td bgcolor="teal"><b>Programming in C</b></td>
</tr>
<tr align ="center">
    <th bgcolor="Cornflowerpink"> 12-1 </th>
    <th colspan="1">LUNCH</th>
    <th bgcolor="blue" colspan="1">MENTOR MEET</th>
    <td colspan="6" align="center"><b>LUNCH</b></td>
</tr>
<tr align ="center">
    <th bgcolor="tan"> 1-3 </th>
    <td > Free SLOT </td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b> </td>
    <td bgcolor="teal"><b> Programming in C</b> </td>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="red"><b> Fundamentals Of Web Development Application</b>
    <td bgcolor="maroon"><b>Advanced Quantitative and Logical Reasoning</b> </td>
</tr>
<tr align ="center">
    <th bgcolor="tan"> 3-5 </th>
    <td> Free Slot </td>
    <td bgcolor="cyan"><b>Problem Solving and Python Programming</b></td>
    <td bgcolor="purple"><b>Intellectual Property Rights</b></td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>
</tr>
</table>
<br>
<br>
<table align="center" border="8" cellspacing="12" cellpadding="12">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td bgcolor="cyan"> 1. </td>
<td bgcolor="cyan"> 19CS301 </td>
<td bgcolor="cyan"> Problem Solving and Python Programming </td>
</tr>
<tr align="center">
<td bgcolor="red"> 2. </td>
<td bgcolor="red"> 19AI414 </td>
<td bgcolor="red"> Fundamentals of Web Application Development </td>
</tr>
<tr align="center">
<td bgcolor="teal"> 3. </td>
<td bgcolor="teal"> 19CS302 </td>
<td bgcolor="teal"> Programming in C </td>
</tr>
<tr align="center">
<td bgcolor="olive"> 4. </td>
<td bgcolor="olive"> 19AI407 </td>
<td bgcolor="olive"> Parallel Computing Arhitecture </td>
</tr>
<tr align="center">
<td bgcolor="purple"> 5. </td>
<td bgcolor="purple"> 19ME531 </td>
<td bgcolor="purple"> Intellectual Property Rights </td>
</tr>
<tr align="center">
<td bgcolor="maroon"> 6. </td>
<td bgcolor="maroon"> 19EY704 </td>
<td bgcolor="maroon"> Advanced Quantitative and Logical Reasoning  </td>
</tr>
</html>
```

## OUTPUT
<img width="960" alt="Screenshot 2024-03-25 204559" src="https://github.com/KirtikRosHan/slot/assets/142528873/6dbd4a6c-08ec-45a6-8539-d91baa8b4875">


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
