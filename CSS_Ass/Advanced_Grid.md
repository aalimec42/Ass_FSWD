
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complex CSS Grid Layout</title>
    <style>
        .grid-container {
            display: grid;
            grid-template-areas:
                'header header header'
                'sidebar content content'
                'footer footer footer';
            grid-template-rows: 100px 1fr 50px;
            grid-template-columns: 200px 1fr 1fr;
            grid-gap: 10px;
        }
        .header { grid-area: header; background-color: lightblue; 
            padding: 10px;
            justify-content: center;
            align-content: center;
            }
        .sidebar { grid-area: sidebar; background-color: lightgreen; 
            padding: 10px;
        }
        .content { grid-area: content; background-color: lightcoral;
            padding: 10px;
         }
        .footer { grid-area: footer; background-color: lightgray; 
        padding: 10px;
    }

  .nested-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            grid-gap: 10px;
        }
        .nested-item1 { background-color: lightyellow; }
        .nested-item2 { background-color: lightpink; }
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="header">Header</div>
        <div class="sidebar">Sidebar</div>
        <div class="content">
            <div class="nested-grid">
                <div class="nested-item1">Nested Item 1</div>
                <div class="nested-item2">Nested Item 2</div>
            </div>
        </div>
        <div class="footer">Footer</div>
    </div>
</body>
</html>
