
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid Layout</title>
    <style>
        .grid-container {
            display: grid;
            grid-template-rows: 100px 200px;
            grid-template-columns: 1fr 2fr;
            grid-gap: 10px;
        }
        .item1 { grid-area: 1 / 1 / 2 / 2; }
        .item2 { grid-area: 1 / 2 / 2 / 3; }
        .item3 { grid-area: 2 / 1 / 3 / 3; }
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="item1">Item 1</div>
        <div class="item2">Item 2</div>
        <div class="item3">Item 3</div>
    </div>
</body>
</html>
