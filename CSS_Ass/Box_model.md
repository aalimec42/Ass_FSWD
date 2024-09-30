...html
      <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Box Model Demonstration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>CSS Box Model Demonstration</h1>
    <div class="box content-box">Content Box</div>
    <div class="box border-box">Border Box</div>
</body>
</html>

...css
     body {
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0;
    padding: 20px;
}

h1 {
    margin-bottom: 20px;
}

.box {
    width: 200px;
    height: 100px;
    margin: 20px;
    padding: 20px;
    border: 10px solid #4CAF50;
    background-color: #f0f0f0;
    text-align: center;
    line-height: 60px;
}

.content-box {
    box-sizing: content-box;
}

.border-box {
    box-sizing: border-box;
}
