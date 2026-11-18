# Ex04 Time Table
## Date:18.11.26

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
<html>
    <head>
        <title>SLOT TIMETABLE</title>
    </head>
    <body>
        <center><img src="logo.png"></center>
        <center>
        <table border="4" cellspacing="10" cellpadding="30" style="font-size: x-large;">
            <caption><h1>SLOT TIMETABE-ARVIND R S (26017022)</h1></caption>
            <tr style="background-color:rgb(127, 244, 255)">
                <th>DAY/TIME</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THRUSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr style="background-color:rgb(140, 127, 255)">
                <th style="background-color:rgb(127, 244, 255)">8:00AM-9:30AM</th>
                <td style="color:white">FREE SLOT</td>
                <td style="color:white">MATHS</td>
                <td style="color:white">MATHS</td>
                <td style="color:white">PYTHON</td>
                <td style="color:white">MATHS</td>
                <td style="color:white">FREE SLOT</td>
            </tr>
            <tr style="background-color:rgb(49, 69, 243)">
                <th style="background-color:rgb(127, 244, 255)">9:45AM-11:15AM</th>
                <td style="color:white">PYTHON</td>
                <td style="color:white">WEB</td>
                <td colspan="2" style="text-align:center;color: white;">FREE SLOT</td>
                <td style="color:white">WEB</td>
                <td style="color:white">CDS</td>
            </tr>
            <tr style="background-color:rgb(140, 127, 255)">
                <th style="background-color:rgb(127, 244, 255)">11:30AM=12:15PM</th>
                <td colspan="5" style="text-align:center;color: white;">FREE SLOT</td>
                <td style="color:white">MENTOR MEET</td>
            </tr>
            <tr style="background-color:rgb(49, 69, 243)">
                <th style="background-color:rgb(127, 244, 255)">12:15PM-1:00PM</th>
                <td colspan="3" style="text-align:center;color: white;">MENTOR MEET</td>
                <td style="color:white">FREE SLOT</td>
                <td style="color:white">MENTOR MEET</td>
                <td style="color:white">FREE SLOT</td>
            </tr>
            <tr style="background-color:rgb(140, 127, 255)">
                <th style="background-color:rgb(127, 244, 255)">1:15PM-2:45PM</th>
                <td style="color:white">WEB</td>
                <td style="color:white">DIGITAL</td>
                <td style="color:white">FREE SLOT</td>
                <td style="color:white">EDM</td>
                <td style="color:white">FREE SLOT</td>
                <td style="color:white">DIGITAL</td>
            </tr>
            <tr style="background-color:rgb(49, 69, 243)">
                <th style="background-color:rgb(127, 244, 255)">3:00PM-4:30PM</th>
                <td style="color:white">FREE SLOT</td>
                <td style="color:white">PYTHON</td>
                <td style="color:white">EDM</td>
                <td style="color:white">FREE SLOT</td>
                <td style="color:white">B EEE</td>
                <td style="color:white">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table border="1" cellspacing="10" cellpadding="30" style="font-size: x-large;">
            <tr>
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMMING(PYTHON)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(WEB)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19MA220</td>
                <td>MATHEMATICS FOR ARTIFICIAL INTELLIGENCE(MATHS)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING(EDM)</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EE404</td>
                <td>DIGITAL ELECTRONICS(DIGITAL)</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19EY708</td>
                <td>CARRER DEVELOPMENT SKILLS(CDS)</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19EE305</td>
                <td>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING(B EEE)</td>
            </tr>







        </table>
        </center>









    </body>













</html>
```

## OUTPUT
![alt text](<Screenshot (19).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
