...html
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style2.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    </head>
<body>
    
 <div class="grid-container">  
    <div class="header">
        <nav>
            <h1>Land Rover Defender</h1>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </div>
    <div class="sidebar">
       
            <h2>Related links</h2><i class='bx bx-link'></i>
            <ol>
                <li><a href="https://www.bing.com/images/search?q=landrover%20defender%20images&form=IQFRML&first=1">Images</a></li>
                <li><a href="https://en.wikipedia.org/wiki/Land_Rover">History</a></li>
                <li><a href="https://www.landrover.in/index.html">Features</a></li>
                <li><a href="https://www.carwale.com/land-rover-cars/defender/110-x-20-petrol-phev/">Prices</a></li>
            </ol>
        </div>
    <div class="main">
        <article>
            <h1>Land Rover with its Unique Defender..</h1>
              <h2>Land Rover since 1978</h2>
              <p>Land Rover was granted a Royal Warrant by King George VI in 1951</p>
              <p>It received a Queen's Award for Enterprise for outstanding contribution to international trade.</p>
            </article>
    </div>
    
   <div class="footer">
        <h3>Reference @ Contact</h3>
        <h3>+91 7654392445|eventgithub@gmail.com</h3>
        <h3>Nehru stadium opp.Avenue park,Chennai,600005</h3>
    
    </div>
    </div>
</body>
</html>


...css
    body{
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}
.grid-container{
    display: grid;
    max-width: var(--dynamic-max-width);
    grid-template-areas: 
    'header header header'
    'sidebar main main'
    'sidebar main main'
    'footer footer footer';
}
.grid-container > div{
    padding: 20px;
    border: 1px solid #ddd;
    text-align: center;

}
.header{
    grid-area: header;
    background-color: rgb(74, 69, 69);
    color: blanchedalmond;
    padding:10px;
    text-align: center;
    nav ul{
        list-style-type:none ;
        padding: 0;
        display:flex;
        justify-content: center;
   }
   nav ul li{
       margin: 0 10px ;
       
   }
   nav ul li a{
       text-decoration: none;
       color: rgb(2, 14, 14);
       box-sizing: content-box;
       background-color: bisque;
       padding: 10px;
       border-radius: 5px;
       &:hover{
           background-color: transparent;
           color: azure;
       }
   }
   h1{
    letter-spacing: 5px;
    
}   
}
.sidebar{
    grid-area: sidebar;
    ol li a{
        text-decoration: none;
        list-style: none;
        height: 100px;
        margin: 10px 5px;
        line-height: 50px;
        width:100px;
        font-size: 18px;
        color: antiquewhite;
        background-color: rgb(46, 41, 41);
        min-width: 25px;
        text-align: center;
        border-radius: 5px;
        padding: 5px;
        &:hover{
            background-color: transparent;
            color: black;
        }
    }
     ol {
        list-style-type: none;
        margin-top: 10px;
    }
    h2{
       color:rgb(46, 41, 41);
       background-color:bisque;
       padding: 5px;
       font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
}
.main{
    grid-area: main;
    article{
        font-family: 'Times New Roman', Times, serif;
        font-size:  20px;
    }
}
.footer{
    grid-area: footer;
    background-color: rgb(74, 69, 69);
    color: blanchedalmond;
    padding:10px;
    text-align: center;

}
