# Ex.03 Slot Time Table
## AIM
  To create slot time table.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the college logo using ```<img>``` tag.

### STEP-3
  Use the ```<table>``` tag with proper cell spacing and cell padding.  

### STEP-4
  Give your name and register number as table title using ```<caption>``` tag.

### STEP-5
  Enter the slot times and days as table header using ```<th>``` tag.
  
### STEP-6
  Type the subjects in the respective slots using ```<tr>``` and ```<td>``` tags.
 
### STEP-7
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
    <title>Time Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color:white;
            margin: 100;
            padding: 300;
        }
        h1 {
            text-align: center;
            color:black;
      }
td {
            padding: 10;
            text-align: center;
        }
        th {
            background-color:WHITE;
            color:black;
        }
    </style>
</head>
<body>
    <h1>TIME TABLE</h1>
    <table border ="2">
        <tr>
<th>Day/Period</th>
<th>I<br>8.00-10.00</th>
<th>II<br>10.00-12.00</th>
<th>Lunch<br>12.00-1.00</th>
<th>III<br>1.00-3.00</th>
</tr>
<tr>
<td><class="highlight">
<b>Monday</b> </td>
<td><br>19AG203</br>Horticulture</td>
<td><br>19AG306</br>Surveying and Levelling</td>
<td> <rowspan="2" class="special"> <b>lunch</b>
</td>
<td><br>19AG301</br>Fluid Mechanics</td>
</tr>

<tr>
<td><class="highlight">
<b>Tuesday</b></td>
<td><br>19MC803</br>Constitution of India</td>
<td><br>19MA203</br>Maths</td>
<td><rowspan="2" class="special"><b>lunch</b></TD>
<td><br>19AG203</br>Horticulture</td>
</tr>

<tr>
<td><class="highlight">
<b>Wednesday</b></td>
<td><br>22HS102</br>Tamils and Technology</td>
<td><br>19AG306</br>Surveying and Levelling</td>
<td><rowspan="2" class="special"><b>lunch</b></td>
<td><br>19EY702</br>Creative Skills</td>
</tr>

<tr>
<td><class="highlight">
<b>Thursday</b></td>
<td><br>19AG201</br>Agronomy</Td>
<td><br>19CS307 </br> Web Designing <br>and</br>Internet Applications</td>
<td><rowspan="2" class="special"><b>lunch</b></Td>
<td><BR>19AG304</BR>Theory of Machines
</td></tr>

<tr>
<td><class="hightlight">
<b>Friday</b></td>
<td><br>ECA-M-AGRI</br>Mentor Meeting</td>
<td><br>19CS307</BR>Web Designing<br>and</br>Internet Applications</Td>
<td><rowspan="2" class="special"><b>lunch</b></td>
<td><br>19MA203</br>Maths</td>
</tr>

</table>
</body>
</html>
```

## OUTPUT
![Screenshot (9)](https://github.com/Vaishnavi204/Ex03_Web-Design/assets/167157596/cf124433-d439-4d1d-95e6-4ee74e7f70cc)



## RESULT
 Slot time table is created successfully.
