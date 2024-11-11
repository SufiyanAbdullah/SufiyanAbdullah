<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation Bar Design</title>
    <script src="https://kit.fontawesome.com/a6a868dc41.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .top-bar {
            background-color: #333;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .social-icons {
            display: flex;
            gap: 10px;
            
        }

        .social-icons a {
            color: #fff;
            text-decoration: none;
            font-size: 14px;
            opacity: 0.8;
        }

        .social-icons a:hover {
            opacity: 1;
        }

        .contact-info {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .phone-number {
            color: #fff;
            text-decoration: none;
            font-size: 14px;
        }

        .call-me-back {
            background-color: #8BC34A;
            color: white;
            padding: 8px 15px;
            border-radius: 4px;
            text-decoration: none;
            font-size: 14px;
            text-transform: uppercase;
        }

        .main-nav {
            background-color: #fff;
            padding: 20px;
            border-bottom: 1px solid #eee;
        }

        .nav-links {
            display: flex;
            justify-content: right;
            gap: 30px;
            list-style: none;
        }

        .nav-links a {
            text-decoration: none;
            color: #474747;
            font-size: 16px;
            text-transform: uppercase;
            font-weight: 500;
            padding: 10px 0;
            position: relative;
        }

        .nav-links a:hover {
            color: #000000;
            border-bottom: solid rgb(255, 238, 0);
        }
    </style>
</head>
<body>
    <div class="top-bar">
        <div class="social-icons">
            <a href="#" title="Facebook" >f</a>
            <a href="#" title="Twitter">tw</a>
            <a href="#" title="Google Plus">g+</a>
            <a href="#" title="LinkedIn">in</a>
            <a href="https://www.youtube.com/@bmjdigitaleducation" title="YouTube">Tube</a>
        </div>
        <div class="contact-info">
            <div>
            <i class="fa-solid fa-phone-flip" style="color: greenyellow;"></i>
            <a href="https://wa.me/923343055013">+92 3168750083</a></div>
            <div>
            <i class="fa-solid fa-phone-flip" style="color: greenyellow;"></i>
            <a href="https://wa.me/923343055013">+92 3168750083</a></div>
            <a href="#" class="call-me-back">CALL ME BACK</a>
        </div>
    </div>
    <nav class="main-nav">
        <ul class="nav-links">
            <li><a href="#">WHY US</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">SERVICES</a></li>
            <li><a href="#">PORTFOLIO</a></li>
            <li><a href="#">PROCESS</a></li>
            <li><a href="#">REVIEWS</a></li>
            <li><a href="#">OUR SKILLS</a></li>
            <li><a href="#">CONTACT US</a></li>
        </ul>
    </nav>
</body>
</html>
