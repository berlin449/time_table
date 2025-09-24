# Ex03 Time Table
# Date:24:09:2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<!-- saved from url=(0029)http://127.0.0.1:5500/tt.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  </head><body><img src="./Slot Time Table_files/sec-logo-01as.png" alt="top image" width="50%" height="20%">

  <title>Slot Time Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 30px;
      background-color:aliceblue;
    }

    h2 {
      text-align: center;
    }

    table {
      width: 75%;
      border-collapse: collapse;
      background-color:(215, 236, 20)lightcoral
    }

    th, td {
      border: 1px solid#452992;
      padding: 12px;
      text-align: center ;
    }

    th {
      background-color:plum;
      color: purple (201, 17, 109);
    }

    td {
      height: 60px;
    }
    tr:nth-child(even)td{
        background-color: aqua;
    }
    
</style>



<h2> Slot Time Table-Maha lakshmi M (25015887)</h2>

<table>
  <tbody><tr>
    <th>Time Slot</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    <th>Saturday</th>
  </tr>
  <tr>
    <td>8:00 - 10:00</td>
    <td>Web</td>
    <td>cryp</td>
    <td>Web</td>
    <td>-</td>
    <td>-</td>
    <td>Cryp</td>
  </tr>
  <tr>
    <td>10:00 - 12:00</td>
    <td>Web</td>
    <td>Cryp</td>
    <td>Web</td>
    <td>-</td>
    <td>Python</td>
     <td>Cryp</td>
  </tr>
     <tr>
    <td>12:00 - 1:00</td>
    <td colspan="6">Lunch Break</td>
  </tr>
  <tr>
    <td>1:00 - 3:00</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>cryp</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>3:00 - 5:00</td>
    <td>-</td>
    <td>-</td>
    <td>Python</td>
    <td>Python</td>
    <td>Python</td>
    <td>-</td>
  </tr>

  </tbody></table><!-- Code injected by live-server -->
 <table>
    
  
  
  
  <h1>Course Details</h1>
    <tr>
      <th>S.No</th>
      <th>Code</th>
      <th>Course</th>
    </tr>
    <tr>
      <td>1</td>
      <td>CS3301</td>
      <td>Python programming</td>
    </tr>
    <tr>
      <td>2</td>
      <td>19AI414</td>
      <td>Fundamental of web application development</td>
      </tr>
    <tr>
      <td>3</td>
      <td>19CS547</td>
      <td>Fundamental of crypto currency</td>
    </tr>
  
  

    </tbody>
  </table>
<script>
```
# OUTPUT
<img width="1920" height="1080" alt="Screenshot 2025-09-22 204951" src="https://github.com/user-attachments/assets/0d31bfd1-8974-4de5-9f8e-9c8b463dfb61" />
<img width="1920" height="1020" alt="Screenshot 2025-09-22 205007" src="https://github.com/user-attachments/assets/cf2b2f4b-3999-4423-a71a-28ed1a06bca7" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
