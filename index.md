<!DOCTYPE html>
<html lang="">

<head>
    <meta charset="utf-8">
    <title>Ali Jlidi</title>
    <meta name="author" content="Your Name">
    <meta name="description" content="Example description">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <meta name="description" content="Welcome to my portfolio My name is Ali Jlidi and I'am full-stack developer skilled in web developement and in the .NET framework , I can build web pages , manipulate data , create video games and desktop softwares" />
    <meta property="og:title" content="Ali Jlidi Developer" />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="http://www.AliJlidiDeveloper.com" />
    <meta property="og:image" content="/images/favicon.png" />
    <link rel="icon" type="image/x-icon" href="/images/favicon.png" />
    <link href="https://fonts.googleapis.com/css?family=Merriweather|Montserrat|Sacramento&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
</head>

<body class="body">
    <nav class="navbar navbar-expand-lg  ">
        <a class="navbar-brand" href="#"><img class="nav-img" src="/images/favicon.png"></a>
        <button class="navbar-toggler navbar-light " type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#Home">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#skills">Skills</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#Projects">Projects</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link " href="#Conatact-me">Contact</a>
                </li>
            </ul>
        </div>
    </nav>


    <div id="Home" class="middle-container">
        <div class="profile">
            <img class="my-pic" src="/images/Avatar.jpg" alt="My picture">
            <h2>Hello.</h2>
            <p class="intro">My name is Ali and I'm an artist , I do anything with passion welcome to my world of Mechanics and technologies ✌.</p>
        </div>
        <hr>
        <div id="skills" class="skills">
            <h2>My Skills.</h2>
            <div class="skill-row">
                <img class="game-pic" src="/images/FirstPic.png" alt="">
                <h3>Game Design</h3>
                <p>I'm a gamer and kind of artist I like discovering art so I tried to understand what is happening behind the curtain where I found scripts ,componennts ,pattern even AI so this is turn to be my geek.</p>
            </div>
            <div class="skill-row">
                <img class="dev-pic" src="/images/SecPic.png" alt="">
                <h3>Full-Stack Developer</h3>
                <p>I started writing scripts from the age of 12 years old by finding solution to some small problems given in classrom then this become a habit practcing it in home and making cool stufs</p>
            </div>
        </div>
        <hr>
        <div id="Projects">
            <h2>My Projects.</h2>
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" data-interval="2000" data-pause="hover">
                <div class="carousel-inner ">
                    <div class="carousel-item active ">
                        <h4> Play and learn</h4>
                        <div class="row">
                            <video class="carousel-video " controls width="30%">
                                <source src="/videos/playAndLearn.webm" type="video/webm">
                                Sorry, your browser doesn't support embedded videos.
                            </video>
                            <p class=" carsousel-paragrpahs col-md-4 col-sm-3 col-xs-3 ">Play and learn it's a project tends to educate children through playing at different levels in which every time we treat a subject like mathematical operations, alphabet, colors, and even breaking puzzles.</p>
                        </div>
                    </div>
                    <div class="carousel-item ">
                        <h4> Master Maint</h4>
                        <div class="row">
                            <video class="carousel-video  " controls width="30%">
                                <source src="/videos/masterMaint.mp4" type="video/mp4">
                                Sorry, your browser doesn't support embedded videos.
                            </video>
                            <p class=" carsousel-paragrpahs col-md-4 col-sm-3 col-xs-3">Mastermaint is a computerized Maintenance Management system, the idea started when I worked with a similar software so I embraced the idea of making a new software with a modern design and better functionalities.</p>
                        </div>
                    </div>
                    <div class="carousel-item ">
                        <h4> Player Controller Unity</h4>
                        <div class="row">
                            <video class="carousel-video" controls width="30%">

                                <source src="/videos/MegaManPrototyping.webm" type="video/webm">

                                Sorry, your browser doesn't support embedded videos.
                            </video>
                            <p class=" carsousel-paragrpahs col-md-4 col-sm-3 col-xs-3">That was when I started learning unity, this is a simple demonstration of a player controller, the character was modeled and animated by me.</p>
                        </div>
                    </div>
                </div>

                <a class="carousel-control-prev " href="#carouselExampleIndicators" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next " href="#carouselExampleIndicators" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>

        </div>
        <hr>
        <div id="Conatact-me" class="contact-me">
            <h2>Get In Touch</h2>
            <h3>ali_jlidi85@yahoo.com</h3>
            <p class="contact-message">Do you like art like me , you are welcome to talk about your ideas and your art .</p>
            <button type="button" class="btn btn-info"><a class="btn" href="mailto:ali_jlidi85@gmail.com">CONTACT ME</a></button>
            <h2>Know more about me</h2>
            <p>Here is my resume ,you can download it so you can know more about me</p>
            <button type="button" class="btn btn-info"><a class="btn" href="mailto:ali_jlidi85@gmail.com">Download</a></button>
        </div>
    </div>


    <div class="bottom-container">
        <a class="footer-link" href="https://www.linkedin.com/in/jlidi-ali-a66296151/">LinkedIn</a>
        <a class="footer-link" href="https://www.facebook.com/profile.php?id=100011862816282">Facebook</a>
        <a class="footer-link" href="https://discordapp.com/channels/@me/639157916787671080">Discord</a>
        <p class="copyright">© 2018 Ali Jlidi.</p>
    </div>

    <script type="text/javascript" src=""></script>
</body></html>
