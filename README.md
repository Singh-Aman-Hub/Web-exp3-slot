# Ex03 Time Table
## Date: 10-04-2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weekly Schedule</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        img {
            width: 540px;
            height: auto;
        }
        h2 {
            margin-top: 20px;
            color: #333;
        }
        table {
            width: 80%;
            margin: 30px auto;
            border-collapse: collapse;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
        }
        th, td {
            padding: 12px 15px;
            border: 1px solid #ddd;
            text-align: center;
        }
        th {
            background-color: #007BFF;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>

    <!-- College Logo -->
    <img src="logo.png" alt="Saveetha Engineering College Logo">

    <!-- Weekly Schedule Table -->
    <h2>Weekly Study Schedule- Aman Singh (Reg no. 212224040020)</h2>
    <table>
        <tr>
            <th>Days/Time</th>
            <th>8hrs - 10hrs</th>
            <th>10hrs - 12hrs</th>
            <th>1hrs - 3hrs</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>DS</td>
            <td>MC</td>
            <td>ML</td>
        </tr>
        <tr>
            <td>Tuesday</td>
            <td>TA</td>
            <td>MC</td>
            <td>MC</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>ML</td>
            <td>WD</td>
            <td>DSA</td>
        </tr>
        <tr>
            <td>Thursday</td>
            <td>DSA</td>
            <td>MOD</td>
            <td>OS</td>
        </tr>
        <tr>
            <td>Friday</td>
            <td>WEB</td>
            <td>DSA</td>
            <td>TEST</td>
        </tr>
    </table>

    <!-- Abbreviations Table -->
    <h2>Course Abbreviations</h2>
    <table>
        <tr>
            <th>Course ID</th>
            <th>Course Name</th>
            <th>Abbreviation</th>
        </tr>
        <tr>
            <td>CS101</td>
            <td>Data Science</td>
            <td>DS</td>
        </tr>
        <tr>
            <td>CS102</td>
            <td>Machine Learning</td>
            <td>ML</td>
        </tr>
        <tr>
            <td>CS103</td>
            <td>Data Structures and Algorithms</td>
            <td>DSA</td>
        </tr>
        <tr>
            <td>CS104</td>
            <td>Web Development</td>
            <td>WD</td>
        </tr>
        <tr>
            <td>CS105</td>
            <td>Module Completion</td>
            <td>MC</td>
        </tr>
        <tr>
            <td>CS106</td>
            <td>Module</td>
            <td>MOD</td>
        </tr>
        <tr>
            <td>CS107</td>
            <td>Operating System</td>
            <td>OS</td>
        </tr>
        <tr>
            <td>CS108</td>
            <td>Task Assignment</td>
            <td>TA</td>
        </tr>
        <tr>
            <td>CS109</td>
            <td>Webinar</td>
            <td>WEB</td>
        </tr>
        <tr>
            <td>CS110</td>
            <td>Test</td>
            <td>TEST</td>
        </tr>
    </table>

</body>
</html>


'''

## OUTPUT

![alt text](<Screenshot (1928).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
