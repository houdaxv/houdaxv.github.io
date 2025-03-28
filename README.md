<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Kanak!</title>
    <style>
        body {
            background-color: #f5f5f5;
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .title {
            font-size: 50px;
            color: #ff6347;
            margin-top: 100px;
        }
        .balloon {
            position: absolute;
            width: 80px;
            height: 120px;
            background-color: #ff69b4;
            border-radius: 50% 50% 40% 40%;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
        }
        .balloon:after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            width: 2px;
            height: 30px;
            background-color: #2e8b57;
            transform: translateX(-50%);
        }
        .balloon1 {
            top: 200px;
            left: 150px;
            background-color: #ff6347;
        }
        .balloon2 {
            top: 250px;
            left: 300px;
            background-color: #ffeb3b;
        }
        .balloon3 {
            top: 180px;
            left: 450px;
            background-color: #00bcd4;
        }
        .balloon4 {
            top: 300px;
            left: 600px;
            background-color: #8e44ad;
        }
        .balloon5 {
            top: 230px;
            left: 750px;
            background-color: #f39c12;
        }
        .confetti {
            position: absolute;
            top: 50px;
            width: 100%;
            height: 100%;
            pointer-events: none;
            animation: fall 3s infinite;
        }
        @keyframes fall {
            0% {
                transform: translateY(-100%);
            }
            100% {
                transform: translateY(100%);
            }
        }
    </style>
</head>
<body>
    <div class="title">Happy Birthday pepper <3</div>
    
    <div class="balloon balloon1"></div>
    <div class="balloon balloon2"></div>
    <div class="balloon balloon3"></div>
    <div class="balloon balloon4"></div>
    <div class="balloon balloon5"></div>
    
    <div class="confetti">
        <!-- You can add images or SVG for confetti here if desired -->
    </div>
</body>
</html>
