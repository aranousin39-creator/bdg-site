---
name: Index.hml
about: 'Enjoy '
title: Bug
labels: ''
assignees: ''

---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BDG Color Prediction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #ff5722;
            color: white;
            padding: 20px 0;
        }
        main {
            padding: 20px;
        }
        .prediction-box {
            display: inline-block;
            margin: 10px;
            padding: 20px;
            width: 120px;
            height: 120px;
            border-radius: 10px;
            font-size: 24px;
            font-weight: bold;
            color: white;
            line-height: 120px;
            cursor: default;
        }
        .red { background-color: #e53935; }
        .green { background-color: #43a047; }
        .blue { background-color: #1e88e5; }
        .yellow { background-color: #fbc02d; color: #000; }
        .invite {
            margin-top: 30px;
        }
        .invite a {
            text-decoration: none;
            background-color: #ff5722;
            color: white;
            padding: 12px 25px;
            border-radius: 5px;
            font-size: 18px;
        }
        footer {
            margin-top: 40px;
            padding: 10px;
            background-color: #ddd;
        }
    </style>
</head>
<body>
    <header>
        <h1>BDG Color Prediction</h1>
        <p>Predict your lottery color and win!</p>
    </header>
    <main>
        <div class="prediction-box red">Red</div>
        <div class="prediction-box green">Green</div>
        <div class="prediction-box blue">Blue</div>
        <div class="prediction-box yellow">Yellow</div>

        <div class="invite">
            <p>Invite your friends:</p>
            <a href="https://bdg3.cc//#/register?invitationCode=7858720480333">Click to Invite</a>
        </div>
    </main>
    <footer>
        &copy; 2026 BDG Prediction. All Rights Reserved.
    </footer>
</body>
</html>
