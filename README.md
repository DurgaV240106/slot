# Ex03 Time Table
## Date:9/11/2023

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
<!DOCTYPE HTML>
<html>
    <head>
       <title>My TimeTable</title>
    </head>
    <body>
        <img src="c:/Users/NAVEEN/slot/durga/slotapp/static/logo.png" height="100" width="540">
        <table border="3" bgcolor="pink">
            <caption align="center"><b>SLOT TIME - TABLE DURGA (23013532)</b></caption>
            <tr bgcolor="blue">
                <th>Day</th>
                <th colspan="2">8.00-10.00</th>
                <th colspan="2">10.00-12.00</th>
                <th colspan="2">12.00-1.00</th>
                <th colspan="2">1.00-3.00</th>
                <th c0lspan="2">3.00-5.00</th>
            </tr>
            <tr>
                <th bgcolor="blue">MON</th>
                <td colspan="2">EDM</td>
                <td colspan="2">CHEMISTRY</td>
                <td colspan="2" rowspan="5" align="center"bgcolor="pink">LUNCH</td>
                <td colspan="2">FREE</td>
                <td colspan="2">FREE</td>
            </tr>
            <tr> 
                <th bgcolor="blue">TUES</th>
                <td colspan="2">FREE</td>
                <td colspan="2">PYTHON</td>
                <td colspan="2">ENGLISH</td>
                <td colspan="2">FREE</td>
            </tr>
            <tr>
                <th bgcolor="blue">WED</th>
                <td colspan="2">WEB</td>
                <td colspan="2">EDM</td>
                <td colspan="2">FREE</td>
                <td colspan="2">PYTHON</td>
            </tr>
            <tr>
                <th bgcolor="blue">THURS</th>
                <td colspan="2">FREE</th>
                <td colspan="2">WEB</td>
                <td colspan="2">ENGLISH</td>
                <td colspan="2">PYTHON</td>
            </tr>    
            <tr>
                <th bgcolor="blue">FRI</th>
                <td colspan="2">PYHTON</td>
                <td colspan="2">FREE</td>
                <td colspan="2">WEB</td>
                <td colspan="2">CHEMISTRY</td>
            </tr>
        </table>
        <br></br>
        <table border="3">
            <tr>
              <th>S.NO</th>
              <th>SUBJECT CODE</th>
              <th>SUBJECT NAME</th>
            </tr>
            <tr>
              <td align="center">1.</td>
              <td align="center">19AI301C</td>
              <td>Python and Linear Algebra</td>
            </tr>
            <tr>  
              <td align="center">2.</td>
              <td align="center">19AI302</td>
              <td>Engineering Design and Modelling</td>
            </tr>
            <tr>
              <td align="center">3.</td>
              <td align="center">19AI414</td>
              <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
              <td align="center">4.</td>
              <td align="center">19CY205</td>
              <td>Principles of Chemistry in Engineering</td>
            </tr>
            <tr>
              <td align="center">5.</td>
              <td align="center">19AI101</td>
              <td>Communicative Engilsh</td>
            </tr>
         </table>
     </body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2023-11-12 073908.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
