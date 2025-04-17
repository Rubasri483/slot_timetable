# Ex03 Time Table
## Date:
17/04/25
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
                 <html>
           <head>
           <title>TIME TABLE</title>
           </head>
            <body>
            <center>
            <img src="/static/logo.png" height="100" width="540">
            </center>
            <br>
            <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - Rubasri.R (212224240139)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
                <th bgcolor="yellow">Saturday</th>

            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td><I>COMMUNICATIVE ENGLISH</I></td>
                <td><I>FREE SLOT</I></td>
                <td><I>ADVANCED C PROGRAMMING</I></td>
                <td><I>PHYSICS FOR QUANTUM COMPUTING</I></td>
                <td><I>FREE SLOT</I></td>
                <td><I>FREE SLOT</I></td>

            </tr>
            <tr align="center">
                <th bgcolor="yellow">10-12</th>
                <td><I>FREE SLOT</I></td>
                <td><I>DIGITAL ELECTRONICS</I></td>
                <td><I>ENGINEERING DESIGN AND MODELLING</I></td>
                <td><I>PROBABILITY AND QUEUEING MODELS</I></td>
                <td><I>FUNDAMENTALS OF WEB APPLICATION</I></td>
                <td><I>FREE SLOT</I></td>

            </tr>
            <tr align="center">
                <th bgcolor="yellow">12-1</th>
                <th colspan="5" align="center"><b>LUNCH BREAK</b></th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td><I>ADVANCED OF C PROGRAMMING</I></td>
                <td><I>PHYSICS FOR QUANTUM COMPUTING</I></td>
                <td><I>MENTOR MEET</I></td>
                <td><I>COMMUNICATIVE ENGLISH</I></td>
                <td><I>FREE SLOT</I></td>
                <td><I>ENGINEERING DESIGNING AND MODELLING</I></td>            
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td><I>FREE SLOT</I></td>
                <td><I>FREE SLOT</I></td>
                <td><I>FREE SLOT</I></td>
                <td><I>FUNDAMENTALS OF WEB APPLICATION</I></td>
                <td><I>DIGITAL ELECTRONICS</I></td>
                <td><I>FREE SLOT</I></td>

            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2" >
            <tr align="center">
                <th>S.no</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING </td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI305</td>
                <td>ADVANCED C PROGRAMMING</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19EE404</td>
                <td>DIGITAL ELECTRONICS</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19MA222</td>
                <td>PROBABILITY AND QUEUEING MODEL</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19PH814</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
        </table>
        </body>
     </html>
     '''

## OUTPUT
![alt text](<Screenshot 2025-04-17 232816.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
