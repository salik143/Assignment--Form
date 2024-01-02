# Assignment--Form
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Form</title>
  </head>
  <body>
    <form  action="https:dummy@xyz" method="post">
        <fieldset>
     First Name: <input type="text" placeholder="First Name" />
      <br />
      <br />
      Last Name: <input type="text" placeholder="Last Name" />
      <br />
      <br />
      Phone #: <input type="number" placeholder="Type Your Number" />
      <br />
      <br />
      Email: <input required type="email" placeholder="Type Your Email" />
      <br />
      <br />
      Password: <input required type="password" placeholder="Type Your Password" />
      <br>
      <br>
      <p><b>Gender</b></p>
      <label for="Male">Male</label>
      <input name="radio value" type="radio" id="Female" />
      <label for="Female">Female</label>
      <input name="radio value" type="radio" id="Female" />
      <br />
      <br />
      <p>Select Your Interest:</p>
      <label for="Sports">Sports</label>
      <input type="checkbox" id="Sports" />
      <label for="Entertainment">Entertainment</label>
      <input type="checkbox" id="Entertainment" />
      <label for="Comedy">Comedy</label>
      <input type="checkbox" id="Comedy" />
      <label for="Adventure">Adventure</label>
      <input type="checkbox" id="Adventure" />
      <br />
      <br />
      <select>
     <option disabled selected value="">Age</option>
        <option></option>
        <option>18</option>
        <option>17</option>
        <option>16</option>
        <option>15</option>
        <option>14</option>
        <option>13</option>
        <option>12</option>
        <option>11</option>
      </select>
      <br>
      <br>
      <input type="Submit"/>
    </form>
  </body>
</html>
