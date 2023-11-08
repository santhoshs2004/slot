# Ex03 Time Table
## Date: 31.10.2023

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
<html>
<head>
    <title>SLOT TIME TABLE</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
    </style>
</head>
<body>
    <img src="/static/logo.png">
    <div class="center-text">
        <h1>SLOT TIME TABLE - SANTHOSH S (212222220039)</h1>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Blue">Day/Time</th>
            <th colspan="1" bgcolor="silver">Monday</th>
            <th colspan="1" bgcolor="Green">Tuesday</th>
            <th colspan="1" bgcolor="orange">Wednesday</th>
            <th colspan="1" bgcolor="purple">Thursday</th>
            <th colspan="1" bgcolor="red">Friday</th>
            <th colspan="1" bgcolor="violet">Saturday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="blue">8-10</th>
            <th rowspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">Maths</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">Maths</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="blue">10-12</th>
    
            <th colspan="1" bgcolor="Cyan">CNS</th>
            <th colspan="1" bgcolor="Cyan">CNS</th>
            <th colspan="1" bgcolor="Cyan">SE</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="cyan">FREE SLOT</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Blue">12-1</th>
            <th colspan="6" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Blue">1-3</th>
            <th colspan="1" bgcolor="Cyan">OS</th>
            <th rowspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th rowspan="2" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">CSFC</th>
            <th colspan="1" bgcolor="Cyan">SE</th>
            <th colspan="1" bgcolor="Cyan">OS</th>
        </tr>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Blue">3-5</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FWAD</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="1" bgcolor="Cyan">FREE SLOT</th>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI414</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19CS408</th>
            <th colspan="2" bgcolor="White">Software Engineering(SE)</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19CS405</th>
            <th colspan="2" bgcolor="White">Operating System(OS)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19MA206</th>
            <th colspan="2" bgcolor="White">Logic and combinatorics(Maths)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19EY702</th>
            <th colspan="2" bgcolor="White">Creative Skills For Communication(CSFC)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19CS412</th>
            <th colspan="2" bgcolor="White">Cryptography And Network Security (CNS)</th> 
        </tr>
    </table>
</body>
</html>

```

## OUTPUT
![Screenshot 2023-11-08 181409](https://github.com/santhoshs2004/slot/assets/129157717/21f9f005-967f-4923-a331-edaab1050f7f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
