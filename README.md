# Ex03 Time Table
# Date:30.3.25
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
<!DOCTYPE html>
<html lang="en">
<head>
    <title>slot time table</title>
</head>
<body>
    <center>
        <img src="/static/logo.png"
        height="100"
        width="540"
    </center>
    <br>
    <table align="center"
    width="540"
    cellspacing="2"
    cellpadding="4"
    border="5"
    bgcolor="fluorescent green">
    <caption><b>slot time table-Nethra.K (24900181)</b></caption>
    <tr align="center">
        <th bgcolor="white">day/time</th>
        <th bgcolor="white">Monday</th>
        <th bgcolor="white">Tuesday</th>
        <th bgcolor="white">Wednesday</th>
        <th bgcolor="white">Thursday</th>
        <th bgcolor="white">Friday</th>
    </tr>
    <tr align="center">
            <th bgcolor="white">8-10</th>
            <td colspan="3" align="center">FREE SLOT</td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr align="center">
            <th bgcolor="white">10-12</th>
            <td>GER</td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>FWAD</td>
            <td>PHY</td>    
        </tr>
        <tr>
            <th bgcolor="white">12-1</th>
            <td colspan="5" align="center">L U N C H B R E A K</td>
        </tr>
        <tr align="center">
            <th bgcolor="white">1-3</th>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
        </tr>
        <tr align="center">
            <th bgcolor="white">3-5</th>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>
        </table>
        <br>
        <table align="center"
        cellspacing="2"
        cellpadding="4"
        border="2">
        <tr align="center">
    
            
        <th>SL.NO</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19AI414</td>
            <td>Fundamental of web Application(FWAD)</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19PH206</td>
            <td>Physics For Information Technology(PHY)</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19EN612</td>
            <td>German Basic(GER)</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19CY205</td>
            <td>Principles of chemistry In Engineering(CHE)</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19MA201</td>
            <td>Calculus And Matrix Algebra(MAT)</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19EY701</td>
            <td>Soft Skills(SS)</td>
        </tr>
        </table>
    </body>
    </html>
    ```
    

    
</body>
</html>
# OUTPUT
c:\Users\admin\Pictures\Screenshots\Screenshot 2025-03-30 220644.png
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
