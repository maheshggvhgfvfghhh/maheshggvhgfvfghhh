<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook – log in or sign up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            text-align: center;
            padding-top: 100px;
        }
        .login-box {
            width: 360px;
            background: white;
            padding: 20px;
            margin: auto;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background: #1877f2;
            color: white;
            padding: 10px;
            width: 100%;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .error {
            color: red;
            display: none;
        }
    </style>
</head>
<body>
    <h1 style="color: #1877f2;">facebook</h1>
    <div class="login-box">
        <h2>Log into Facebook</h2>
        <input type="text" id="email" placeholder="Email or Phone">
        <input type="password" id="password" placeholder="Password">
        <button onclick="fakeLogin()">Log In</button>
        <p class="error" id="error">Incorrect email or password.</p>
    </div>

    <script>
        function fakeLogin() {
            document.getElementById("error").style.display = "block"; // Hamesha error show karega
        }
    </script>
</body>
</html>
