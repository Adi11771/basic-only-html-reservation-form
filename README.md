<html>
<head>
<title>reservation form</title>
<h1><b>A meeting room reservation form</b></h1>
</head>
<body align="center">
<table align="center" cellpadding="12" cellspacing="0">
 <tr>
     <td>Your Name:</td>
     <td><input type="text" name="fname" required></td>
 </tr>
 <tr bgcolor="#D0CDCD">
     <td>YourEmail:</td>
     <td> <input type="email" name="mail" required></td>
 </tr>
 <tr>
     <td>department:</td> 
     <td> <select>
                 <option value="select">-select-</option>
                 <option value="AC">AC</option>
                 <option value="NON-AC">NON-AC</option>
          </select></td>
 </tr>
 <tr bgcolor="#D0CDCD">
      <td> which room would like to reserve:</td>
      <td> 
          <input type="radio" name="room">room a 
          <input type="radio" name="room">room b
          <input type="radio" name="room">room c
      </td>
 </tr>
 <tr>
      <td>Extra requirements</td>
      <td>
          <input type="checkbox" value="flipchair&pens">flipchair&pens <br>
          <input type="checkbox" name="plasma tv screen">plasma tv screen <br>
          <input type="checkbox" name="coffee">coffee
     </td>
 </tr>
 <tr bgcolor="#D0CDCD">
     <td>Reservation Date:</td>
     <td>
         <input type="date" id="d" name="d">
     </td>
 </tr>
 <tr>
     <td> Reservation Time:</td>
     <td><input type="time"id="t" name="t" pattern="scroll" ></td>
 </tr>
 <tr bgcolor="#D0CDCD">
      <td></td>
      <td><input type="submit" value="Submit"></td>
 </tr>
</table>
</body>
</html>
