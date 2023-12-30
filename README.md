# Ex03 Time Table
## Date:

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
<center>
   <head>
    <title>🗓️TIME TABLE🗓️</title>
    <link rel="icon" href="https://media.discordapp.net/attachments/533340656987275284/906080541344956436/kissclipart-saveetha-university-chennai-logo-clipart-saveetha-3a90c06681798db2.png" type="image/icon type">
  </head>
   <body>
      <table border = "1" cellspacing="1" bordercolor="#C19A6B" bgcolor="transparent">
         <tr>
            <th colspan="8">TIME TABLE</th>
            <br></br>
	 <table border = "1" cellspacing="1" bordercolor="#C19A6B" bgcolor="transparent">
    <br></br>
<img src="https://cdn.discordapp.com/attachments/533340656987275284/914068516334891028/logo.png" width="662" height="100">
 <tr>
 <th colspan="8">TIME TABLE</th>
 </tr>
 <tr>
  <br></br>
<th colspan="4">Name:Nikshitha G </th> 
<th colspan="4">Reference Number:23007784 </th> 
         </tr>
         
         <tr>
            <th>DAYS</th>
            <th>1</th>
            <th>2</th>
            <th>3</th>
            <th>4</th>
         </tr>



         <tr>
             <td align="center">MONDAY</td>
             <td align="center">19AI301C/Bhuvaneswari G</td>
             <td align="center">---</td>
             <td align="center">19AI303/Sellakumar S</td>
             <td align="center">19PH214/Sivakumar T</td>
             
         </tr>
	 <tr>
             <td align="center">TUESDAY</td>
             <td align="center">19EN101/Hemalatha V</td>
             <td align="center">---</td>
             <td align="center">19AI301C/Bhuvaneswari G</td>
             <td align="center">---</td>
             
         </tr>
	 <tr>
             <td align="center">WEDESDAY</td>
             <td align="center">19AI303/Sellakumar S</td>
             <td align="center">19AI414/Michael Devine</td>
             <td align="center">19AI301C/Bhuvaneswari G</td>
             <td align="center">---</td>
             
         </tr>
	 <tr>
             <td align="center">THURSDAY</td>
             <td align="center">---</td>
             <td align="center">---</td>
             <td align="center">---</td>
             <td align="center">19AI414/Michael Devine</td>
             
         </tr>
  	 <tr>
             <td align="center">FRIDAY</td>
             <td align="center">19AI414/Michael Devine</td>
             <td align="center">19PH214/Sivakumar T</td>
             <td align="center">19AI301C/Bhuvaneswari G</td>
             <td align="center">19EN101/Hemalatha V</td>
            
         </tr>
         
      </table>
      <h2><u>Enrolled Subject</u></h2>
<H3>1. 19AI414 - Fundamentals of web application</H3>
<H3>2. 19EN101 - Communicative English</H3>
<H3>3. 19PH214 - Physics For Quantum Computing</H3>
<H3>4. 19AI301C - Python And Linear Algebra</H3>
<H3>5. 19AI303 - Engineering Mechanics And Product Development</H3>
<center><br><br><div class="footer">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="copyright-text">
                <p>
                  © 2023
                  
                </p>
              </div>
            </div>
          </div>
        </div>
      </div></br></br></center>

      
   </body>

</body>
  <style>
    body {
      background: linear-gradient to right, (#ADD8EF, #FFB6C1);
      color: #333333;
      font-family: "Euclid Circular B Medium", Poppins;
    }
     <script>
    .footer {
      padding: 32px 0;
      position: absolute;
      width: 100%;
      background-color: red;
      color: white;
      text-align: center;
      background: rgba(255, 255, 255, 0.5);
      box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
      backdrop-filter: blur(9px);
      -webkit-backdrop-filter: blur(9px);
      border: 1px solid rgba(255, 255, 255, 0.18);
    }
    .footer p {
      margin: 0;
      line-height: 26px;
      font-size: 15px;
      color: #990099;
    }
    .footer p a {
      background: linear-gradient(to right, #f27121, #e94057, #8a2387);
      color: transparent;
      -webkit-background-clip: text;
      background-clip: text;
      text-decoration: none;
    }
    .footer p a:hover {
      color: white;
    }
  </style>
</html>
```

## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
