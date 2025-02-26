<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Love Manar ❤️</title>
    <style>
        body {
            background: linear-gradient(to right, #ffcccc, #ff99cc);
            text-align: center;
            font-family: 'Arial', sans-serif;
        }
        .container {
            margin-top: 80px;
            padding: 20px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
            display: inline-block;
        }
        h1 {
            color: #ff3366;
            font-size: 3em;
            text-shadow: 2px 2px 5px #ff6699;
        }
        p {
            color: #333;
            font-size: 1.4em;
            margin: 15px;
        }
        .heart-button {
            background-color: #ff3366;
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 1.5em;
            cursor: pointer;
            border-radius: 30px;
            transition: transform 0.2s, background-color 0.3s;
            box-shadow: 0 5px 15px rgba(255, 51, 102, 0.3);
        }
        .heart-button:hover {
            transform: scale(1.1);
            background-color: #cc0044;
        }
        .hidden-message {
            display: none;
            color: #ff1a1a;
            font-size: 2em;
            margin-top: 20px;
            font-weight: bold;
        }
        .heart {
            font-size: 5em;
            color: red;
            animation: heartbeat 1.5s infinite;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Dear Manar ❤️</h1>
        <p>You are the light of my life, my heart beats only for you.</p>
        <p>Every moment with you is a beautiful blessing, and I am the luckiest man to have you.</p>
        <div class="heart">❤️</div>
        <button class="heart-button" onclick="showMessage()">Click to see my heart ❤️</button>
        <p id="message" class="hidden-message">I LOVE YOU, MANAR! ❤️💖</p>
    </div>
    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
