<html>
<head>
  <title>The Regal Fern</title>
  </head>
<body bgcolor="pink">
<center><font face="Algerian"></center>
  <center><h1>The Regal Fern</h1></center>
<br><br>

 <center><h2>User Registration Form</h2></center>
  <form action="#" method="post">
    <label for="fname">First Name:</label><br>
    <input type="text" id="fname" name="fname" required><br><br>

    <label for="lname">Last Name:</label><br>
    <input type="text" id="lname" name="lname" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="phone">Phone Number:</label><br>
    <input type="tel" id="phone" name="phone" required><br><br>
 <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required><br><br>

    <label for="confirm">Confirm Password:</label><br>
    <input type="password" id="confirm" name="confirm" required><br><br>

    <label for="gender">Gender:</label><br>
    <input type="radio" id="male" name="gender" value="male" required> Male
    <input type="radio" id="female" name="gender" value="female"> Female<br><br>

    <label for="dob">Date of Birth:</label><br>
    <input type="date" id="dob" name="dob" required><br><br>

    <label for="address">Address:</label><br>
    <textarea id="address" name="address" rows="3" cols="30"></textarea><br><br>

 <input type="submit" value="Register">
    <input type="reset" value="Clear">
</form>
</body>
</html>
