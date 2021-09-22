<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<title>Display</title>
	<link rel="stylesheet" href="css/main.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
	</head>
  <style>
  
		*{
			margin: 0;
			padding: 0;
			box-sizing: border-box;
            font-family: 'compacta-regular', sans-serif;
		}
        
        .wrapper{
            position: relative;
            background-image: url(../images/banner.jpg);
            width:100%;
            height: 100vh;
            background-size: cover;
            background-position: center;
        }
        .navbar{
            /* background-color: #000; */
            color: #fff;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        .navbar .logo img{
            height:30px;
        }
        .navbar .nav-items {
            list-style: none;
        }
        .navbar .nav-items .nav-links{
            display:inline-block;
            padding: 20px 10px;
        }
        .navbar .nav-items .nav-links a{
            text-decoration: none;
            color: #fff;
            font-size: 12px;
            position: relative;
        }
        .navbar .nav-items .nav-links a::after{
            content: '';
            width:0;
            height:3px;
            position: absolute;
            bottom: -5px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #E50914;
            transition: width 0.3s;
        }
        .navbar .nav-items .nav-links a:hover::after{
            width:50%;
        } 
        .navbar .nav-items .nav-links img{
            width: 20px;
        }
        .menu-line{
            width:2rem;
            height: 3px;
            background-color: #fff;
            margin-bottom:4px;

        }
        .menu{
            display:none;
        }
        
        .text-box{
            position: absolute;
            left: 0;
            bottom:7%;
            color: #fff;
            padding: 0 14%;
        }
        .text-box h4{
            font-size: 1rem;
            font-weight: 500;
            line-height: 40px;
        }
        .text-box p{
            width:50%;
            font-size: 0.75rem;
            line-height: 20px;
            font-family: sans-serif;
        }
        .text-box .row{
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .text-box a{
            color: #333;
            text-decoration: none;
            padding: 10px 15px;
            margin-right: 20px;
            border: 1px solid #fff;
            background-color: #fff;
            font-family: sans-serif;
            font-size: 0.87rem;
            border-radius: 3px;
        }
        .text-box img{
            height: 0.93rem;
        }
        .text-box span {
            margin: 0.62rem;
        }
        .text-box h1{
            font-size: 3.75rem;
            line-height: 90px;
            text-transform: uppercase;
            color:transparent;
            -webkit-text-stroke: 1px #fff;
            background: url(../images/back.png);
            -webkit-background-clip: text;
            background-position:0 0;
            animation: back 20s linear infinite;
        }
        @keyframes back {
            100%{
                background-position: 2000px 0;
            }
        }
         /* Mobile Css */
         
         @media only screen and  (max-width:480px) {
             .navbar{
                 flex-direction: column;
                 
             }
             .menu{
                 display:block;
                 position: absolute;
                 top:20px;
                 right: 20px;
             }
             .logo{
                 width:100%;
                 padding: 15px;
             }
             .navbar .nav-items{
                 display: none;
             }
             .active{
                 display: block;
             }
             .text-box{
                 position: absolute;
                 bottom: 10%;
                 padding: 20px;
             }
             .text-box h1{
                 font-size:35px;
                 line-height: 50px;
             }
             .text-box p{
                 width:100%;
             }
         }
  </style>
	<body>
		<section class="wrapper">
			<header class="navbar">
			<div class="logo">
				<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/2560px-Netflix_2015_logo.svg.png" alt="logo">
			</div>
			<nav>
			<ul class="nav-items" id="navi-links">
				<li class="nav-links">
					<a href="#">HOME</a>
				</li>
				
				<li class="nav-links">
					<a href="#">TV SHOW</a>
				</li>
				
				<li class="nav-links">
					<a href="#">MOVIES</a>
				</li>
				
				<li class="nav-links">
					<a href="#">LATEST</a>
				</li>
				
				<li class="nav-links">
					<a href="#">MY LIST</a>
				</li>
				<li class="nav-links">
					<a href="#">FAVOURITE</a>
				</li>

			</ul>
			</nav>
			<div class="menu" id="toggle-button">
				<div class="menu-line"></div>
				<div class="menu-line"></div>
				<div class="menu-line"></div>
			</div>
		</header>
		<div class="text-box">
				<h4>Netflix Series Original</h4>
				<img src="images/star.png" alt="">
				<span>2017</span>
				<span>5 Episode</span>
				<h1>Money Heist</h1>
				<p>Eight thieves take hostages and lock themselves in
					the Royal Mint of Spain as a criminal mastermind manipulates the police to carry out his plan.</p>
					
				<div class="row">
					<a href=""><i class="fas fa-play"></i> Watch Now </a>
					<a href=""><i class="fas fa-info-circle"></i> More Info</a>
				</div>
			</div>
	</section>
		
		<script>
			var toggle = document.querySelector("#toggle-button");

			toggle.addEventListener("click" , function(){
				this.classList.toggle("active");
			});
		</script>
	</body>
	</html>


