<html>
<head>
<body><center>
        <label for="username"><h1 style="font-size: 45px; color: rgb(195, 255, 0);">REGISTRATION FORM</h1></label>
  <style>
h2 {
  text-align: center;
}
.input-group {
  margin-bottom: 50px;
}
.label {
  display: block;
  margin-bottom: 20px;
}
input[type="text"],
input[type="email"],
input[type="password"] {
  width: 40%;
  padding: 10px;
  border: 1px solid #00ff37;
  border-radius: 5px;
}
button {
  width: 60%;
  height:10%;
  padding: 2px;
  background-color: #00ff37;
  color: #ffffffc9;
  border: none;
  border-radius: 0.5px;
  cursor: pointer;
}
button:hover {
  background-color: #0056b3;
}
body {
      font-family: Arial, sans-serif;
      background-image: url("1.jpg");
      background-size: cover;
      background-position: center;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 900px;
      margin: 20px auto;
      padding: 30px;
      background-color: #d4ff66a9;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      border-radius: 300px;
    }
  </style>
</head>
<body>
  <div class="container">
    <form action="#">
      <div class="input-group">
        <label for="username"><h2 style="font-size: 25px; color: rgb(0, 26, 255);">USERNAME</h2></label>
        <input type="text" id="username" required>
      </div>
      <div class="input-group">
        <label for="email"><h2 style="font-size: 25px; color: rgb(255, 0, 0);">EMAIL</h2></label>
        <input type="email" id="email" required>
      </div>
      <div class="input-group">
        <label for="password"><h2 style="font-size: 25px; color: rgb(123, 0, 255);">PASSWORD</h2></label>
        <input type="password" id="password" required>
      </div>
      <button type="submit"><h2 style="font-size: 30px; color: rgb(255, 0, 179);"><center>SUBMIT</center></h2></button>
    </form>
  </center>
</body>
</html>
