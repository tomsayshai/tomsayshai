<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Netflix Login</title>
  <style>
    body {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      background-color: #000;
      color: #fff;
    }

    .login-container {
      text-align: center;
      max-width: 400px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .login-container h1 {
      font-size: 2em;
    }

    .input-group {
      margin-top: 20px;
    }

    .input-group input {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: none;
      border-radius: 4px;
    }

    .input-group button {
      width: 100%;
      padding: 10px;
      background-color: #e50914;
      border: none;
      border-radius: 4px;
      color: #fff;
      font-size: 1.2em;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h1>Netflix</h1>
    <div class="input-group">
      <input type="text" placeholder="Username">
      <input type="password" placeholder="Password">
      <button onclick="login()">Log In</button>
    </div>
  </div>

  <script>
    function login() {
      // Add your login logic here
      alert("Login button clicked");
    }
  </script>
</body>
</html>
