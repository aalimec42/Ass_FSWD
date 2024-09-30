<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Layout</title>
    <style>
        .container {
            display: flex;
            flex-direction: row; /* Arrange items in a row */
            justify-content: space-between; /* Distribute space between items */
            align-items: center; /* Center items vertically */
            height: 100vh; /* Full viewport height */
            padding: 20px;
            background-color: #f0f0f0;
        }
        .item {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 5px;
            flex: 1; /* Allow items to grow and shrink */
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="item">Item 1</div>
        <div class="item">Item 2</div>
        <div class="item">Item 3</div>
    </div>
</body>
</html>

