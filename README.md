# Ex02 Time Table
## Date:28/11/25

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
        <center>
            <img src="logo.png" height="100" width="540"
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="6" bgcolor="pink">
            <caption><b>SLOT TIMETABLE</b></caption>
            <tr align="center">
                <th bgcolor="orange">Day/Time</th>
                <th bgcolor="pink">MONDAY</th>
                <th bgcolor="pink">TUESDAY</th>
                <th bgcolor="pink">WEDNESDAY</th>
                <th bgcolor="pink">THURSDAY</th>
                <th bgcolor="pink">FRIDAY</th>
                <th bgcolor="pink">SATURDAY</th>
            </tr>
            <tr align="center">
            <th bgcolor="orange">8-10</th>
            <td>C program</td>
            <td>Free</td>
            <td>C Program</td>
            <td>Free</td>
            <td>FWAD</td>
            <td>Free</td>
            </tr>
            
            <tr align="center">
            <th bgcolor="orange">10-12</th>
            <td>Free</td>
            <td>Free</td>
            <td>Free</td>
            <td>CE</td>
            <td>FWAD</td>
            <td>FWAD</td>
            </tr>

            <tr align="center">
            <th bgcolor="orange">12-1</th>
            <td colspan="6" align="center">LUNCH BREAK </td>
            </tr>

            <tr align="center">
            <th bgcolor="orange">1-3</th>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>Mentor Meet</td>
            <td>c Program</td>
            <td>C Program</td>
            <td>C Program</td>
            </tr>

            <tr align="center">
            <th bgcolor="orange">3-5</th>
            <td>C Program</td>
            <td>Free</td>
            <td>CE</td>
            <td>Free/td>
            <td>Free/td>
            <td>CE</td>
            </tr>
        </table>
        <br><br>
        <table align="center" border="6" bgcolor="yellow">
            <tr>
                <th><b>S.NO</b></th>
                <th><b>SUBJECT CODE</b></th>
                <th><b>SUBJECT NAME</b></th>
            </tr>

             <tr>
                <th><font color="yellow">1</font></th>
                <th><font color="brown">19AI414</font></th>
                <th><font color="red">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</font></th>
            </tr>

             <tr>
                <th><font color="yellow">2</font></th>
                <th><font color="brown">19AI304</font></th>
                <th><font color="red">FUNDAMENTALS OF C PROGRAMMING</font></th>
            </tr>

            <tr>
                <th><font color="yellow">3</font></th>
                <th><font color="brown">19EN101</font></th>
                <th><font color="red">COMMUNICATIVE ENGLISH</font></th>
            </tr>

        </table>
    </body>
</html>





```


## OUTPUT

![alt text](<Screenshot (23).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
