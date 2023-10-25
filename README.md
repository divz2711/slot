# Ex03 Time Table
# Date: 05/10/2023

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

## CODE
```
<!DOCTYPE html>
<html>
<head>
<title>SLOT TIME TABLE - Divya S</title>
</head>
<body>

<img src="C:\Users\divya\OneDrive\Desktop\Lit club\logo1.png" alt="Google Logo" style="display: block; margin: 0 auto;">
<h4>SLOT TIME TABLE - Divya Sampath (212221040042)</h4>

<table border="1" style="background-color: lightblue;">
<tr>
<th style="background-color: yellow;">Day/Time</th>
<th style="background-color: yellow;">Monday</th>
<th style="background-color: yellow;">Tuesday</th>
<th style="background-color: yellow;">Wednesday</th>
<th style="background-color: yellow;">Thursday</th>
<th style="background-color: yellow;">Friday</th>
</tr>
<tr>
<td style="background-color: yellow;">8-10</td>
<td colspan="3"><center>FREE SLOT</center></td>
<td>PHY</td>
<td>CHE</td>

</tr>
<tr>
<td style="background-color: yellow;">10-12</td>
<td>GER</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>FWAD</td>
<td>PHY</td>
</tr>
<tr>
<td style="background-color: yellow;">12-1</td>
<td colspan="5">LUNCH</td>

</tr>
<tr>
<td style="background-color: yellow;">1-3</td>
<td colspan="2">FREE SLOT</td>
<td>MAT</td>
<td>MAT</td>
<td>SS</td>
</tr>
<tr>
<td style="background-color: yellow;">3-5</td>
<td colspan="2">FREE SLOT</td>
<td>GER</td>
<td>CHE</td>
<td>FWAD</td>
</tr>
</table>

<br>

<table border="1">
<tr>
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development (FWD)</td>
</tr>
<tr>
<td>2.</td>
<td>19EN612</td>
<td>German Basic (GER)</td>
</tr>
<tr>
<td>3.</td>
<td>19PH206</td>
<td>Physics for Information Technology (PHY)</td>
</tr>
<tr>
<td>4.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td>5.</td>
<td>19MA201</td>
<td>Calculus and Matrix Algebra (MAT)</td>
</tr>
<tr>
<td>6.</td>
<td>19EY701</td>
<td>Soft Skills (SS)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![Screenshot 2023-10-19 160850](https://github.com/divz2711/slot/assets/121245222/21095299-afa4-4ba5-84cb-672a8a644164)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
