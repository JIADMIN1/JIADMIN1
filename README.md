<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up - UCE App</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body class="signup-page">
    <div class="app-logo">
        <h1>UCE Logo</h1> <!-- Replace with actual logo image if available -->
    </div>
    <div class="welcome-popup" id="welcomePopup">
        <p>Hello! Welcome to UCE. You are on your way to breaking through financial crisis; don't give up yet.</p>
        <button onclick="closePopup()">Thanks</button>
    </div>

    <div class="signup-container">
        <h1>Create an Account</h1>
        <form id="signupForm">
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="regCode">Registration Code:</label>
                <input type="text" id="regCode" name="regCode" required>
                <p>The code is required for account registration. Registering code is required for account creation.</p>
            </div>
            <div class="form-group">
                <label>
                    <input type="checkbox" id="terms" name="terms" required>
                    I agree to the <a href="terms.html" target="_blank">terms and conditions</a>.
                </label>
            </div>
            <div class="form-group">
                <a href="https://wa.me/2349049307270" target="_blank">Request Registration Code</a>
            </div>
            <button type="submit">Verify Code</button>
        </form>
    </div>

    <script src="js/script.js"></script>
</body>
</html>
