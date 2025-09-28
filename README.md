<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f3f4f6;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .login-container {
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
      width: 300px;
    }

    .login-container h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }

    .login-container input[type="text"],
    .login-container input[type="password"] {
      width: 100%;
      padding: 12px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      box-sizing: border-box;
    }

    .login-container button {
      width: 100%;
      padding: 12px;
      background: #4CAF50;
      border: none;
      color: white;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 10px;
    }

    .login-container button:hover {
      background: #45a049;
    }

    .login-container .links {
      text-align: center;
      margin-top: 12px;
    }

    .login-container .links a {
      color: #4CAF50;
      text-decoration: none;
      font-size: 14px;
    }

    .login-container .links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="login-container">
    <h2>Login</h2>
    <form action="login.php" method="POST">
      <input type="text" placeholder="Username" name="username" required>
      <input type="password" placeholder="Password" name="password" required>
      <button type="submit">Login</button>
    </form>
    <div class="links">
      <p><a href="#">Forgot Password?</a></p>
      <p><a href="#">Create an Account</a></p>
    </div>
  </div>

</body>
</html>
