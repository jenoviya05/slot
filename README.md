# Ex03 Time Table
## Date:20.09.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Slot Timetable</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background-color: #f4f4f4;
    }
    h2 {
      text-align: center;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      background-color: #fff;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 12px;
      text-align: center;
    }
    th {
      background-color: #007BFF;
      color: white;
    }
    td {
      height: 60px;
    }
    tr:nth-child(even) td {
      background-color: #f9f9f9;
    }
  </style>
</head>
<body>

<h2>Weekly Slot Timetable</h2>
<center>
    <img src="/static/logo.png" height="100" width="540">
</center>

<table>
  <tr>
    <th>Day</th>
    <th>8:00 - 10:00</th>
    <th>10:00 - 12:00</th>
    <th>01:00 - 03:00</th>
    <th>03:00 - 05:00</th>
  </tr>
  <tr>
    <td>Monday</td>
    <td>English</td>
    <td>free</td>
    <td>Web</td>
    <td>Python</td>
  </tr>
  <tr>
    <td>Tuesday</td>
    <td>free</td>
    <td>Python</td>
    <td>English</td>
    <td>free</td>
  </tr>
  <tr>
    <td>Wednesday</td>
    <td>English</td>
    <td>English</td>
    <td>web</td>
    <td>Mentor_meet</td>
    <td>Web</td>
  </tr>
  <tr>
    <td>Thursday</td>
    <td>free</td>
    <td>free</td>
    <td>English</td>
    <td>Web</td>
  </tr>
  <tr>
    <td>Friday</td>
    <td>English</td>
    <td>Python</td>
    <td>free</td>
    <td>English</td>
  </tr>
</table>

</body>
</html>
~~~


## OUTPUT
![alt text](<Screenshot 2025-09-20 145045.png>)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
