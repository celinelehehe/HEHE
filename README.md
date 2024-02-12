<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Red Envelope Choices</title>
    <style>
        body {
            background-color: #f8f9fa;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .choices-container {
            display: flex;
            gap: 20px;
        }

        .red-envelope {
            width: 150px;
            height: 200px;
            background-color: #ff4d4d;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #ffffff;
            font-size: 20px;
            font-weight: bold;
            text-align: center;
            cursor: pointer;
            transition: transform 0.3s ease-in-out;
        }

        .red-envelope:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <div class="choices-container">
        <div class="red-envelope">Choice 1</div>
        <div class="red-envelope">Choice 2</div>
        <div class="red-envelope">Choice 3</div>
        <div class="red-envelope">Choice 4</div>
    </div>

</body>
</html>

