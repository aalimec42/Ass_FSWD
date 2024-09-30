<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complex Flexbox Layout</title>
    <style>
        .container {
            display: flex;
            flex-wrap: wrap;
            align-content: space-between;
            gap: 10px;
            height: 100vh;
        }
        .item {
            flex: 1 1 30%;
            background-color: lightcoral;
            padding: 20px;
            margin: 10px;
            color: white;
            text-align: center;
        }
        .nested-container {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .nested-item {
            background-color: lightseagreen;
            padding: 10px;
            color: white;
        }
        .order-1 {
            order: 1;
        }
        .order-2 {
            order: 2;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="item order-2">
            Item 1
            <div class="nested-container">
                <div class="nested-item">Nested Item 1</div>
                <div class="nested-item">Nested Item 2</div>
            </div>
        </div>
        <div class="item order-1">Item 2</div>
        <div class="item">Item 3</div>
        <div class="item">Item 4</div>
        <div class="item">Item 5</div>
    </div>
</body>
</html>

