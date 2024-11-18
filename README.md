# Ex03 Time Table
## Date:
16.11.2024
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
    <body>
        <img src="logo.png"  width="700" height="100">
<table border="2" cellspacing="15" cellpadding="5">
    <caption>SLOT TIMETABLE-ANS NERLING EMIMA S(24900105)</caption>
    <tr bgcolor="lavender">
    <th>DAY/TIME</th>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
    <th>FRI</th>
    <th>SAT</th>
    </tr>
    <tr>
    <th>8-10</th>
    <td>FREE SLOT</td>
    <td>WEB</td>
    <td colspan="4">FREE SLOT</td>
    </tr>
    <tr>
    <th>10-12</th>
    <td>ENGLISH</td>
    <td>MATHS</td>
    <td>C PROG</td>
    <td>CaAREER</td>
    <td>C PROG</td>
    <td>MATHS</td>
    </tr>
    <tr>
    <th>12-1</th>
    <td colspan="6">LUNCH</td>
    </tr>
    <tr>
    <th>1-3</th>
    <td>BEE</td>
    <td>ENGLISH</td>
    <td>MENTOR MEET</td>
    <td>BEEE</td>
    <td>WEB</td>
    <td>WEB</td>
    </tr>
    <tr>
    <th>3-5</th>
    <td colspan="2">FREE SLOT</td>
    <td>CHEMISTRY</td>
    <td>CHEMISTRY</td>
    <td colspan="2">FREE SLOT</td>
    </tr>
    </table>
 
    <table border="2" cellspacing="15" cellpadding="5">
    <caption COURSES>
    <tr bgcolor="cyan">
    <th>S.NO</th>
    <th>COURSE CODE</th>
    <th>COURSE NAME</th>
    </tr>
    <tr>
    <td>1</td>
    <td>19AI304</td>
    <td>C PROGRAMMInG</td>
    </tr>
    <tr>
    <td>2</td>
    <td>19AI414</td>
    <td>WEB APPLICATION</td>
    </tr>
    <tr>
    <td>3</td>
    <td>19CY205</td>
    <td>PRINCIPLES OF CHEMICAL ENGINEERING</td>
    </tr>
    <tr>
    <td>4</td>
    <td>19EY708</td>
    <td>CAREER DEVELOPMENT</td>
    </tr>
    <tr>
    <td>5</td>
    <td>19EE305</td>
    <td>BASICS OF ELECTRICAL ENGINEERING</td>
    </tr>
    <tr>
    <td>6</td>
    <td>ECA-M-SCOFT</td>
    <td>MENTOR MEET</td>
    </tr>
    <tr>
    <td>7</td>
    <td>19MA201</td>
    <td>CALCULUS AND MATRIX ALGEBRA</td>
    </tr>
    </table>
    </body>
</html>
       
    

```
## OUTPUT
![alt text](<Screenshot 2024-11-18 084905.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
