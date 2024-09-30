
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Images</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Responsive Images Example</h1>
        <img src="image-small.jpg" >
             
    </div>
</body>
</html>
srcset="image-small.jpg 600w, image-medium.jpg 1200w, image-large.jpg 1800w" 
             sizes="(max-width: 600px) 100vw, (max-width: 1200px) 50vw, 33vw" 
             alt="A beautiful scenery">
