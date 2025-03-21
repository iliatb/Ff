<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Social Media</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background: #000;
            color: white;
        }
        .container {
            text-align: center;
            background: rgba(30, 30, 30, 0.9);
            padding: 30px;
            border-radius: 25px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.6);
            max-width: 320px;
            border: 2px solid white;
        }
        h1 {
            margin-bottom: 15px;
            color: white;
            text-shadow: 0 0 10px white;
        }
        .links a {
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 12px 0;
            padding: 15px;
            width: 100%;
            background: #fff;
            color: black;
            text-decoration: none;
            border-radius: 20px;
            transition: 0.3s ease-in-out;
            font-weight: bold;
            border: 2px solid white;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
        }
        .links a:hover {
            background: #ccc;
            transform: scale(1.08);
            box-shadow: 0 0 20px white;
        }
        .wallet {
            margin-top: 20px;
            padding: 10px;
            background: #111;
            border-radius: 20px;
            border: 2px solid white;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
            text-align: center;
        }
        .wallet p {
            margin: 0;
            font-size: 14px;
            text-shadow: 0 0 5px white;
        }
        .wallet input {
            margin-top: 10px;
            padding: 10px;
            width: 100%;
            border: none;
            border-radius: 10px;
            text-align: center;
            font-size: 14px;
            background: #222;
            color: white;
            border: 2px solid white;
            box-shadow: 0 0 10px white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>My Social Media</h1>
        <div class="links">
            <a href="https://t.me/Iliatbb" target="_blank">Telegram</a>
            <a href="https://instagram.com/iliatb" target="_blank">Instagram</a>
        </div>
        <div class="wallet">
            <p>My Crypto Wallet:</p>
            <input type="text" value="UQAalXA5mzVNxjjoXERBP6Ca8oUqH_UJ0uZIlOTJhd37EMuS" readonly>
        </div>
    </div>
</body>
</html>
