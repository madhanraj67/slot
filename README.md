# Ex03 Time Table
## Date:14:3:2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Timetable</title>
</head>
<body><center>
    <img src="logo.png"  height="100" >
    
    <h3>SLOT TIME TABLE-MADHANRAJ(23013616)</h3>
    <table  align="center" bgcolor="orange"border="6"cellspacing="3" cellpadding="7" width="540">
        <tr  bgcolor="green">
            <th >Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
         </tr>  
         <tr  bgcolor="orange">
            <th  bgcolor="green">8-10</th>
            <td colspan="3"  align="center" >FREE SLOT</td>
            <td>PHY</td>
            <td>CHE</td>
         </tr> 
         <tr  bgcolor="orange">
            <th  bgcolor="green">10-12</th>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
         </tr> 
         <tr  bgcolor="orange">
            <th  bgcolor="green">12-1</th>
            <td colspan="5" align="center">L U N C H</td>
         </tr> 
         <tr  bgcolor="orange">
            <th  bgcolor="green">1-3</th>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
         </tr> 

    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="4" border="6">
        <tr>
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
        </tr>
        <tr>
            <th>1</th>
            <th>19AI414</th>
             <td colspan="3">Fundamental Of Web Application Developement(FWAD)</td>
        </tr>
        <tr>
            <th>2</th>
            <th>19AI414</th>
             <td >German Basic(GER)</td>
        </tr>
        <tr>
            <th>3</th>
            <th>19AI414</th>
             <td >Physics For Information Technology (PHY)</td>
            
        </tr>
        <tr>
            <th >4</th>
            <th>19AI414</th>
             <td >Principle Of Chemistry In Engineering(CHE)</td>
        </tr>
        <tr>
            <th>5</th>
            <th>19AI414</th>
             <td >Calculas And Matrix Algebra(MAT)</td>
        </tr>
        <tr>
            <th>6</th>
            <th>19AI414</th>
             <td >Soft Skill(SS)</td>
        </tr>
   
    </table> </center>
    
</body>
</html>
```

## OUTPUT
![Screenshot 2024-03-20 094855](https://github.com/madhanraj67/slot/assets/150319515/47f9ef09-1c92-4b17-a26f-daeb5d4f3a25)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
