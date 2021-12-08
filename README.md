# HomeDesign.html
Design your home
*{
    margin: 0;
    padding: 0;
    font-family: serif;
}
.banner{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.65),rgba(0,0,0,0.65)),url(logo2.jpg);
    background-size: cover;
    background-position: center;
}
.navbar{
    width: 1px;
    margin: auto;
    padding: 18px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.navbar ul li{
    list-style: none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
}
.navbar ul li a{
    text-decoration: none;
    color: #fff;
    text-transform: uppercase;
}
.navbar ul li::after{
    content: '';
    height: 3px;
    width: 0;
    background: #009688;
    position: absolute;
    left: 0;
    bottom: -10;
    transition: 0.5s;
}
.navbar ul li:hover::after{
    width: 100%;
}
.content{
    width: 100%;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
    color: #fff;
}
.content h1{
    font-size: 39px;
    margin: 30px;
}
.content p{
    margin: 20px auto;
    font-weight: 100;
    line-height: 25px;
}
button{
    width: 139px;
    padding: 15px 0;
    text-align: center;
    margin: 20px 10px;
    border-radius: 25px;
    font-weight: bold;
    border: 2px solid #009688;
    background: transparent;
    color: #fff;
    cursor: pointer;
    position: relative;
    overflow: hidden;
}
span{
    background: #009688;
    height: 100%;
    width: 0%;
    border-radius: 25px;
    position: absolute;
    left: 0;
    bottom: 0;
    z-index: -1;
    transition: 0.5s;
}
button:hover span{
    width: 100%;
}
button:hover{
    border: none;
}


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <title>best home design</title>
  
  <script src="main.js"></script>
   
  <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="banner">
  <div class="navbar">
    <ul>
      <li> <a href="#">Home</a> </li>
      <li> <a href="#">Bedroom</a> </li>
      <li> <a href="#">Dining</a> </li>
      <li> <a href="#">Kitchen</a> </li>
    </ul>
  </div>
  <div class="content">
    <h1>DESIGN YOUR HOME</h1>
    <p>Look for the best design that fits your home on our website<br />As we are proud helping you design your home to fit your taste<p>
      <div>
        <button type="button"><span></span>Learn More</button>
        <button type="button"><span></span>Continue</button>
      </div>
  </div>
</div>
</body>
</html>
