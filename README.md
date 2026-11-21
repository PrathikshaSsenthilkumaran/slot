# Ex04 Time Table
## Date:21/11/2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
slot.html
<html>
    <head>
        <title> TIMETABLE</title>
        
    </head>
    <body bgcolor="">
        <center>
<img src="logo.png" width="800">
<h2>my TIME TABLE - Prathiksha(26002593)</h2>
<table border="1" cellspacing="5" cellpadding="10">
    <tr bgcolor="lightblue">
        <th>DAY/TIME</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    <tr>
        <td bgcolor="cyan">8 - 9:30</td>
        <td bgcolor="babypink">CA</td>
        <td bgcolor="babypink">MATH AI</td>
        <td bgcolor="babypink">MATH AI</td>
        <td bgcolor="babypink">PYTHON</td>
        <td bgcolor="babypink">MATH AI</td>
        <td bgcolor="babypink">PYTHON</td>
       
    </tr>
    <tr>
        <td bgcolor="cyan">9:45 - 11:15</td>
        <td bgcolor="babypink">PYTHON</td>
        <td bgcolor="babypink">FWAD</td>
        <td bgcolor="babypink">FREE SLOT</td>
        <td bgcolor="babypink">JAP</td>
        <td bgcolor="babypink">FWAD</td>
        <td bgcolor="babypink">CA</td>
    </tr>
    <tr>
        <td bgcolor="cyan">1:15 - 2:45</td>
        <td bgcolor="babypink">FWAD</td>
        <td bgcolor="babypink">SOFT</td>
        <td bgcolor="babypink">FREE SLOT</td>
        <td bgcolor="babypink">CDS</td>
        <td colspan="2" bgcolor="babypink">FREE SLOT</td>
    </tr>
    <tr>
        <td bgcolor="cyan">3 - 4:30</td>
        <td bgcolor="babypink">CRY</td>
        <td bgcolor="babypink">CRY</td>
        <td colspan="3" bgcolor="babypink">FREE SLOT</td>
        <td bgcolor="babypink">JAP</td
    </tr>




    
</table>
</center>
<br>
<center>
<table border="1" cellspacing="5" cellpadding="8">
    <tr bgcolor="nyan" >
        <th> S.NO </th>
        <th>SUBJECT CODE</th>
        <th>SUBJECT NAME </th>
     </tr>
     <tr>
        <td>1.</td>
        <td>19AI414</td>
        <td>Fundamentals of web application development(FWAD)</td>
     </tr>
     <tr>
        <td>2.</td>
        <td>19AI301</td>
        <td>Python programming(PYTHON)</td>
        
     </tr>
     <tr>
        <td>3.</td>
        <td>19CS305</td>
        <td>Computer architecture(CA)</td>
     </tr>
     <tr>
        <td>4.</td>
        <td>19GE624</td>
        <td>Japanese language N5 basic(JAP)</td>
     </tr>
     <tr>
     <td>5.</td>
     <td>19AI302</td>
     <td>software engineering(soft)</td>
</tr>
<tr>
    <td>6.</td>
    <td>19MA220</td>
    <td>Mathematics for artificial intelligence(MATH AI)</td>
</tr>

<tr>
    <td>7.</td>
    <td>19EY708</td>
    <td>Career development skill(CDS)</td>
</tr>
<tr>
    <td>8.</td>
    <td>19EE305</td>
    <td>cyber law(CYL)</td>
</tr>

</table>
</center>

    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (28).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
