<?php
include_once 'azurroheader.php';
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="azurrostyle.css" media="screen"/>
    <title>AzurroFirstPage</title>
</head>
<body>
                <div class="main">
                        <div class="text">
                           <h3>Private site for Azurro Garden owners.</h>
                           <h3>...........................................</h>            
                        </div>

                        <div class = "btn">
                          <a href="<?php echo base_url()?>azurropassword.php"><button type="button" class="first-btn" >Enter information for apartment</button></a>
                          <a href="<?php echo base_url()?>azurrocheck.php"><button type="button" class="second-btn">Check information for apartment</button></a>
                        </div>
                        
                       <div class = "mainpic">
                       
                            <div class = "mainpic1">
                            <h4>Pics : </h4>
                                    <img src="galery/august.jpg" alt="azurro1" width="272px" height="200px">
                            </div>
                            
                            <div class = "mainpic2">
                            <h4>Pics : </h4>
                                    <img src="galery/august1.jpg" alt="azurro2" width="272px" height="200px">
                            </div>

                            <div class = "mainpic3">
                            <h4>Pics : </h4>
                                    <img src="galery/august2.jpg" alt="azurro3" width="272px" height="200px">
                            </div>
                            
                       </div>   
                          
                       
          
                       </div>

                </div>  
</body>
</html>
<?php
include_once 'azurrofooter.php';
?>

