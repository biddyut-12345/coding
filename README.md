<!DOCTYPE html>
<html lang="en">
<head>
     <title>Proposal for Jupi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #ffcccc, #ffe6e6);
            color: #333;
            text-align: center;
            padding: 50px;
            margin: 0;
        }
        h1 {
            font-size: 3em;
            color: #d63384;
        }
        p {
            font-size: 1.5em;
            margin: 20px 0;
        }
        .heart {
            font-size: 5em;
            color: #ff0000;
            animation: pulse 1s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        button {
            font-size: 1.2em;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .yes {
            background-color: #28a745;
            color: white;
        }
        .no {
            background-color: #dc3545;
            color: white;
        }
        .no:hover {
            background-color: #c82333;
        }
    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Will You Be My Girlfriend, Jupi?</h1>
    <div class="heart">❤️</div>
    <p>Hey Jupi, I've been captivated by your smile from the moment I saw it. It's the kind of smile that lights up the whole room and makes my day brighter. I really like you, and I hope you'll say yes to being mine!</p>
    <p>What do you say?</p>
    <button class="yes" onclick="alert('Yay! I\'m so happy! Let\'s celebrate!')">Yes! 😊</button>
    <button class="no" onclick="alert('Oh no! But I\'ll keep trying to win you over with my charm!')">No 😢</button>
</body>
</html>
