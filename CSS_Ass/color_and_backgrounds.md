html...
     <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Color Properties Demo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>CSS Color Properties Demo</h1>
    <div class="color-example">This text uses the `color` property.</div>
    <div class="background-color-example">This div uses the `background-color` property.</div>
    <div class="gradient-example">This div uses a gradient background.</div>
    <div class="background-image-example">This div uses a background image.</div>
</body>
</html>

css...
   body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    padding: 20px;
}

h1 {
    color: #333;
    text-align: center;
}

.color-example {
    color: #ff6347; 
    margin: 20px 0;
}

.background-color-example {
    background-color: #add8e6; 
    padding: 20px;
    margin: 20px 0;
}

.gradient-example {
    background: linear-gradient(to right, #ff7e5f, #feb47b);
    padding: 20px;
    margin: 20px 0;
    color: white;
}

.background-image-example {
    background-image: url('https://via.placeholder.com/150');
    background-repeat: no-repeat;
    background-position: center;
    padding:  80px 70px;
    margin: 20px 0;
    color: white;
    text-align: center;
    
}
