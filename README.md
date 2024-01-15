# Try-to-hack-this-site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 100px;
        }

        #login-form {
            max-width: 300px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div id="login-form">
        <h2>Login</h2>
        <form action="welcome.html" method="post">
            <label for="username">Gebruikersnaam:</label>
            <input type="text" id="username" name="username" required><br>

            <label for="password">Wachtwoord:</label>
            <input type="password" id="password" name="password" required><br>

            <input type="submit" value="Login">
        </form>
    </div>
</body>
</html>


