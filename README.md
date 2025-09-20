<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Document</title>
    <style>
        .header{
            border: 2px solid red;
            background-color: brown;
            color: white;
            text-align: center;
            grid-column-start: 1;
            grid-column-end: 4;
        }
        .main{
            border: 2px solid cornflowerblue;
            background-color: blueviolet;
            grid-column-start: 2;
            grid-column-end: 4;
        }
        .sidebar{
            border: 2px solid orange;
            background-color: aqua;
            grid-column-start: 1;
            grid-column-end: 2;
        }
        .footer{
            border: 2px solid pink;
            background-color: green;
            grid-column-start: 1;
            grid-column-end: 4;
        }
        .gridcontainer{
            display: grid;
            grid-template-columns: 1fr 3fr;
        }

    </style>
</head>
<body>
    <header>
        <div>
        <h1 class="header">header</h1>
    </div>

    </header>
    <div class="gridcontainer"m>
    <!-- <header>
        <div>
        <h1 class="header">header</h1>
    </div>

    </header> -->
    <main class="main">Main
        
    </main>
    <main class="sidebar">sidebar</main>
    <footer class="footer">
        <p>copyaright2025</p>
    </footer>
    </div>

</body>
</html>
