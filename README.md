# Password-Input

<input>
type="password"
When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. They are hidden in this way so that if someone is looking over the user's shoulder, they cannot see sensitive data such as passwords.
name
The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.
size, maxlength
It can also carry the size and maxlength attributes like the the single-line text input.

<form action="http://www.example.com/login.php">
  <p>Username:
    <input type="text" name="username" size="15" maxlength="30" />
  </p>
  <p>Password:
   <input type="password" name="password" size="15" maxlength="30" />
  </p>
</form>
