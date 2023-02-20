# gym-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Club</title>
</head>
<link href="https://fonts.googleapis.com/css2?family=Balsamiq+Sans&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    /*css Reset*/
    body{
        font-family: 'Balsamiq Sans',cursive;
        color:white;
        margin:2px;
        padding:2px;
        background: url('img/gympic.JPEG');
        background-size: 100%;
    }
    .left{
        display: inline-block;
        /* border: 2px solid green; */
        position:absolute;
        left:40px;
        top:8px;
    }
    .left img{
        width: 85px;
        filter:invert(100%);

    }
    .left div{
        text-align: center;
        font-size: 17px;
        line-height: 25px;
    }
    .mid{
        display: block;
        width: 36%;
        margin: 20px auto;
        /* border: 2px solid rebeccapurple; */

    }
    .right{
        position: absolute;
        right: 34px;
        top:33px;
        display: inline-block;
        /* border: 2px solid blue; */
    }
    .navbar{
        display: inline-block;

    }
    .navbar li{
        display:inline-block;
        font-size: 16px;
    }
    .navbar li a{
        color:white;
        text-decoration: none;
        padding:33px 17px;
    }
    .navbar li a:hover,
    .navbar li a.active{
        text-decoration: underline;
        color: gray;
    }
    .btn{
        font-family: 'Balsamiq Sans',cursive;
        margin:0px 9px;
        color:white;
        background-color: black;
        padding:4px 14px;
        border: 2px solid gray;
        border-radius: 10px;
        font-size: 14px;
        cursor: pointer;
    }
    .btn:hover{
        background-color: rgb(95, 102, 95);
    }
    .container{
        border:2px solid red;
        margin: 55px 50px;
        padding:43px 45px;
        border: 5px solid white;
        border-radius: 38px;
        width:30%;
    }
    .form-group input{
        text-align: center;
        display: block;
        width: 346px;
        padding: 2px;
        margin:9px auto;
        border: 2px solid black;
        font-size: 16px;
        border-radius: 8px;
        font-family: 'Balsamiq Sans',cursive;
    }
    .container h1{
        text-align: center;
    }
    .container button{
        display: block;
        width:40%;
        margin:30px auto;
    }
</style>
<body>
    <header class="'header">
        <!-- Left box for logo -->
        <div class="left">
            <img src="img/gymlogo.jpg" alt="" >
            <div>Fitness Club</div>

        </div>
        <!-- Mid box for navigation -->
        <div class="mid">
            <ul class="navbar">
                <li><a href='#' class="active">Home</a></li>
                <li><a href='#'>About Us</a></li>
                <li><a href='#'>Fitness Calculator</a></li>
                <li><a href='#'>Contact Us</a></li>
            </ul>

        </div>
        <!-- Right box for buttom -->
        <div class="right">
            <button class="btn">Call Us Now</button>
            <button class="btn">Email Us</button>

        </div>
    </header>
    <div class="container">
        <h1>Join the best Gym of the Bhubneswar now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Address">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Phone Number">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>
</html>
