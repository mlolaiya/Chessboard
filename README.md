# Chessboard
A 5x5 chessboard created mainly with HTML and CSS


<!-----------------CSS---------------!>
* {
    margin: 0;
    padding: 0;
    background-color: #000;
    
  

}
<!-----------------SPECIFYING THE CONTAINER SIZE---------------!>
.chessboard {
    width: 500px;
    height: 500px;
    margin: 50px;
    border: 20px solid #c6ccc9;
    left: 30%;
    position: absolute;
   
  
}

<!-----------------GREEN BOXES---------------!>
.green {
    width: 100px;
    height: 100px;
    float: left;
    background-color: #259c5b;
    font-size: 70px;
    text-align: center;
    vertical-align: middle;

}


<!-----------------EHITE BOXES---------------!>
.white {
    width: 100px;
    height: 100px;
    float: left;
    background-color: #c6ccc9;
    font-size: 70px;
    text-align: center;
    vertical-align: middle;
}



<!-----------------HTML CODE---------------!>
<html>
<head>
    <title>chessboard</title>
</head>
<body>
    <div class="chessboard">
                    <!-- 1st row -->
                <div class="white">&#9820;</div>
                <div class="green">&#9822;</div>
                <div class="white">&#9821;</div>
                <div class="green">&#9819;</div>
                <div class="white">&#9818;</div>
            
                
                    <!-- 2nd row -->
                <div class="green">&#9823;</div>
                <div class="white">&#9823;</div>
                <div class="green">&#9823;</div>
                <div class="white">&#9823;</div>
                <div class="green">&#9823;</div>
                
                
                    <!-- 3rd row -->
                <div class="white"></div>
                <div class="green"></div>
                <div class="white"></div>
                <div class="green"></div>
                <div class="white"></div>
            
                
                    <!-- 4th row -->
                <div class="green">&#9817;</div>
                <div class="white">&#9817;</div>
                <div class="green">&#9817;</div>
                <div class="white">&#9817;</div>
                <div class="green">&#9817;</div>
                
                
                    <!-- 5th row -->
                <div class="white">&#9814;</div>
                <div class="green">&#9816;</div>
                <div class="white">&#9815;</div>
                <div class="green">&#9813;</div>
                <div class="white">&#9812;</div>       
    </div>
</body>
</html>
