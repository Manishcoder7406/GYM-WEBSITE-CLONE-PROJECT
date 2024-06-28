# GYM-WEBSITE-CLONE-PROJECT
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manish's Fitness</title>
</head>
<link rel="stylesheet" href="css/style.css">
<style>
    /*CSS RESet */
    body{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-weight:bolder;
        margin: 0px;
        padding: 0px;
        background: url('img/gym.jpg');
        color: white;
        
    }
    .left{
        display: inline-block;
        /* border: 2px solid red; */
        left: 60px;
        position: absolute;
        top: 20px;
    }
    .left img{
        width: 136px;
    }
    .left div{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-weight: bolder;
        text-align: center;
    }
    .mid{
        display: block;
        width: 43%;
        margin: 29px auto;
        /* border: 2px solid green; */
    }
    .right{
        position: absolute;
        right: 34px;
        top: 43px;
        display: inline-block;
        /* border: 2px solid yellow; */
    }
    .navbar{
        display: inline-block;
    }
    .navbar li{
        color: white;
        display: inline-block;
        font-size: 20px;
    }
    .navbar li a{
        color: white;
        text-decoration: none;
        padding: 34px 23px;
    }
    .navbar li a:hover,.navbar li a:active{
        text-decoration: underline;
        color: grey;
    }
    .btn{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-weight: bolder;
        margin: 0px 9px;
        background-color:black ;
        color: white;
        padding: 4px 14px;
        border-radius: 10px;
        font-size: 20px;
        cursor:pointer;
    }
    .btn:hover{
        background-color: rgb(57, 56, 56);
    }
    .container{
        border: 2px solid white;
        margin: 150px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }
    .form-group input{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-weight: bolder;
        text-align: center;
        display: block;
        width: 500px;
        padding: 2px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;
    }
    .container h1{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-weight: bolder;
        text-align: center;
    }
    .container button{
        display: block;
        width: 500px;
        margin: 20px auto;
    }
    
</style>
<body>
    <header class="header">
        <!-- left box for logo    -->
        <div class="left">
            <img src="img/logo2.jpg" alt="">
            <div>Manish's Fitness</div>
        </div>
        <!-- mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
        <!-- right box for butons -->
        <div class="right">
              <button class="btn">Call us </button><button class="btn">Email us</button>      
        </div>
    </header>
    <div class="container">
        <h1>JOIN THE BEST GYM OF LUDHIANA</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your phone no.">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your location">
            </div>
            <button class="btn">SUBMIT</button>
        </form>
            
    </div>
    
</body>
</html>
