
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive web page Media queries</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            display: grid;
            grid-template-columns: 1fr;
            grid-gap: 10px;
            padding: 10px;
        }
        .header, .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
        .main {
            background-color: #f4f4f4;
            padding: 10px;
        }
        .sidebar {
            background-color: #ddd;
            padding: 10px;
        }

  /* Mobile styles */
        @media (max-width: 600px) {
            .container {
                grid-template-columns: 1fr;
            }
            .header, .footer {
                font-size: 14px;
            }
            .sidebar {
                display: none;
            }
        }

 /* Tablet styles */
        @media (min-width: 601px) and (max-width: 1024px) {
            .container {
                grid-template-columns: 1fr 1fr;
            }
            .header, .footer {
                font-size: 16px;
            }
            .sidebar {
                display: block;
            }
        }

   /* Desktop styles */
        @media (min-width: 1025px) {
            .container {
                grid-template-columns: 1fr 3fr;
            }
            .header, .footer {
                font-size: 18px;
            }
            .sidebar {
                display: block;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">Header</div>
        <div class="main">Main Content</div>
        <div class="sidebar">Sidebar</div>
        <div class="footer">Footer</div>
    </div>
</body>
</html>
