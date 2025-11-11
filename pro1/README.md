# Ex03 Time Table
## Date:11-11-2025

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

time.html

```
<!DOCTYPE html>
<html>
<head>
  <title>Timetable</title>
</head>
<body>
    <center>
        <image src="/static/logo.png" alt="Logo" width="500" height="100">
    </center>
    <center> <h2>SLOT TIME TABLE</h2></center>
 
  <table border="1" cellspacing="0" cellpadding="5" align="center" width="700">
    <tr bgcolor="#ffcc99">
      <th>Time</th>
      <th>Sunday </th>
      <th>Monday </th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday </th>
      <th>Friday </th>
      <th>Saturday </th>
    </tr>

    <tr>
      <td>8:00am-10:00am</td>
      <td></td>
      <td>Fundamentals of C Programming</td>
      <td>Transforms and its Applications</td>
      <td>Fundamentals of Artificial Intelligence</td>
      <td>Introduction to Machine Learning</td>
      <td>Environmental Sciences and Sustainability</td>
      <td></td>
    </tr>
    <tr>
      <td> 10:00am-12:00pm </td>
      <td></td>
      <td>Introduction to Machine Learning</td>
      <td></td>
      <td>Fundamentals of Web Applications</td>
      <td>Transforms and its Applications</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>12:00pm-1:00pm</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>1:00pm-3:00pm</td>
      <td></td>
      <td>Fundamentals of Web Applications</td>
      <td></td>
      <td>Mentor Meet </td>
      <td>Fundamentals of C Programming</td>
      <td>Fundamentals of Artificial Intelligence</td>
      <td></td>
    </tr>
    <tr>
      <td>3:00pm-5:00pm</td>
      <td></td>
      <td>Software Engineering </td>
      <td></td>
      <td>Quantitative Ability </td>
      <td>Software Engineering </td>
      <td>GATE (3411)</td>
      <td></td>
    </tr>
  </table>
  <table border="1" align="center" border="1" cellspacing="0"cellpadding="3">
  <caption><h2>SUBJECT CODE</h2></caption> 
  <tr bgcolor="#ffcc99"> 
    <th>S. No.</th> 
    <th>Subject Code</th> 
    <th>Subject Name</th> 
  </tr> 
  <tr> 
    <td>1</td> 
    <td>19AI414</td> 
    <td>Fundamentals of Web Application Development (FWAD)</td> 
  </tr> 
  <tr> <td>2</td> 
    <td>19AI410</td> 
    <td>Introduction to Machine Learning</td> 
  </tr> 
  <tr> <td>3</td> 
    <td>19AI304</td> 
    <td>Fundamentals of C Programming</td> 
  </tr> 
  <tr > 
    <td>4</td> 
    <td>19CS408</td> 
    <td>Software Engineering</td> 
  </tr> 
  <tr> 
    <td>5</td> 
    <td>19MA219</td> 
    <td>Transform and its Application</td> 
  </tr> 
  <tr > 
    <td>6</td> 
    <td>19EY710</td> 
    <td>Quantitative Ability</td> 
  </tr> 
  <tr > 
    <td>7</td> 
    <td>19AI405</td> 
    <td>Fundamentals of Artificial Intelligence</td> 
  </tr> 
 </table>
 </body>
</html>

```


## OUTPUT

![alt text](<Screenshot 2025-11-11 233155.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
