# azurro



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="azurrostyle.css" media="screen"/>
    <title>Index1</title>
</head>
<body>
    <div class="header">
        <a href="#default" class="logo">Azurro Owners</a>
        <div class="header-right">
            <a class="active" href=http://localhost:8080/cars/firstpage.php>Home</a>
            <a href="#check">Check</a>
            <a href="#contact">Contact</a>
            <a href="#about">Help</a>

        </div>

    </div>

    <div class="main">
        <div class="text">
            <h3>Private site for Azurro Garden owners.</h3>
            <h3>......................................</h3>
        </div>
        <form action="azurroindex2.php" method="POST">

            <label for="fname">Name of owner:</label><br>
            <input type="text" id="fullname" name="fullname" placeholder="Enter your name.."><br>

            <label for="apartnumber">Number of apartment:</label><br>
            <input type="text" id="apartnumber" name="apartnumber" placeholder="Enter your apartment number.."><br><br>

            <label for="garagenumber">Number of garage:</label><br>
            <input type="text" id="garagenumber" name="garagenumber" placeholder="Enter your garage number .."><br><br>

            
            <input type="submit" id="submitbuton" value="Submit"><br><br>

            <!-- <input type="image" src="checkimages.jpg" id= "checkbuton" alt="Submit" width="48" height="48">-->
        </form>
    </div>

    <footer>
        <h3>Footer name</h3>
        <div class="footer-links">
            <a href="#home">Home</a>
            <a href="#blog">Blog</a>
            <a href="#about">About</a>
            <a href="#fac">Faq</a>
            <a href="#contact">Contact</a>
        </div>

        <p class="footer-company-name">ogi.matov &copy; 2020</p>

    </footer>
</body>
</html>
