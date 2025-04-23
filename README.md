# Ex03 Time Table
## Date:22/04/25

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
'''
''
<pre><code>
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta <name="viewport" content="width=device-width,initial-scale=1.0"></name>
        <title>table</title>
        </head>
        <body bgcolor="cyan">
            <img src="/static/logo.png" height="100" width="540">
            <table border="5" cellpadding="20" bg color="orange" align="center">
                <tr>
                    <th bgcolor="red">TIME</th>
                    <th bgcolor="red">MONDAY</th>
                    <th bgcolor="red">TUESDAY</th>
                    <th bgcolor="red">WEDNESDAY</th>
                    <th bgcolor="red">THURSDAY</th>
                    <th bgcolor="red">FRIDAY</th>
                    <th bgcolor="red">SATURDAY</th>
                </tr>
                <tr>
                    <th bgcolor="red">8-10</th>
                    <td>-</td>
                    <td>DATASCIENCE</td>
                    <td>DIGITAL ELECTRONICS</td>
                    <td>PHYSICS</td>
                    <td>-</td>
                    <td>-</td>
                </tr>
                <tr>
                    <th bgcolor="red">10-12</th>
                    <td>WEB DEVELOPMENT</td>
                    <td>DATASCIENCE</td>
                    <td>WEB DEVELOPMENT</td>
                    <td>CHEMISTRY</td>
                    <td>ENGLISH</td>
                    <td>PHYSICS</td>
                </tr>
                <tr>
                    <th bgcolor="red">1-3</th>
                    <td>PHYSICS</td>
                    <td>DIGITAL ELECTRONICS</td>
                    <td>MENTOR MEET</td>
                    <td>ENGLISH</td>
                    <td>DATASCIENCE</td>
                    <td>WEB DEVELOPMENT</td>
                </tr>
            </table>
        </body>
</html>
    </code></pre>
'''
## OUTPUT
![image](https://github.com/user-attachments/assets/5c75e295-abfd-485e-8cda-4be17ac5d82c)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
