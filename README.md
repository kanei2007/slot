# Ex03 Time Table
## Date:23/04/25

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
<!DOCTYPE html><html>
<head>
    <title>Class Timetable</title>
    <style>
        table {
            width: 60%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: yellow;
        }
        .highlight {
            background-color: lightblue;
        }
    </style>
</head>
<body>
<center>
    <img src="/static/logo.png" height="100" width="750">

    
<h2>Class Timetable</h2>
<table>
    <tr>
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
    </tr>
    <tr class="highlight">
        <td>8-10</td>
        <td>OS</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>OS</td>
        <td>FREE SLOT</td>
    </tr>
    <tr class="highlight">
        <td>10-12</td>
        <td>FREE SLOT</td>
        <td>CALCULUS</td>
        <td>HUMAN VALUES</td>
        <td>FWAD</td>
        <td>GAME PRG</td>
        
    </tr>
    <tr>
        <td>12-1</td>
        <td colspan="5">LUNCH</td>
    </tr>
    <tr class="highlight">
        <td>1-3</td>
        <td>EEE</td>
        <td>FWAD</td>
        <td>MENTOR</td>
        <td>GAME PRG</td>
        <td>CALCULUS</td>
    </tr>
    <tr class="highlight">
        <td>3-5</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
        <td>EEE</td>
        <td>FREE SLOT</td>
        <td>FREE SLOT</td>
    </tr>
</table>

<h2>Subject Details</h2>
<table>
    <tr>
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19EE305</td>
        <td>EEE</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19CS405</td>
        <td>Operating system</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19HS801</td>
        <td>Human values and professional ethics</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra (MAT)</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19AL513</td>
        <td>Game programming</td>
    </tr>
   
</table>
</center>

</body>
</html>
                
## OUTPUT

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
