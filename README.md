<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta charset="viewpoint" content="width=device-width, initial-scale=1.0">
    <title>Steven's Portfolio</title>

    <link rel="stylesheet" href="styles.css">

    <link href="https://fonts.googleapis.com/css?family=Source+Code+Pro:400,900|Source+Sans+Pro:300,900&display=swap"
    rel="stylesheet">

    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous">


</head>
<body>
    <header>
        <div class="logo">
            <h2>Welcome</h2>
        </div>
    <button class="nav-toggle" aria-label="toggle navigation">
        <span class="hamburger"></span>
    </button>
    <nav class="nav">
        <ul class="nav__list">
            <li class="nav__list"><a href="#home" class="nav__link">Home</a></li>
            <li class="nav__list"><a href="#about" class="nav__link">About Me</a></li>
            <li class="nav__list"><a href="#skills" class="nav__link">Skills</a></li>
            <li class="nav__list"><a href="#contact" class="nav__link">Contact</a></li>
        </ul>
    </nav>
    </header>

    <!-- Intro -->
    <section class="intro" id="home">
        <h1 class="section__title section__title--intro">
            Hello, I'm <strong>Steven Samera</strong>
        </h1>
        <p class="section__subtitle section__subtitle--intro">IT Support Specialist/Engineer/Developer</p>
        <img class="image" src="images/FullSizeRender.jpg" alt="Steven's Pose">

    </section>

    <!-- About Me -->
    <section class="about-me" id="about">
        <h2 class="section__title section__title-about">Allow me to introduce myself</h2>
        <p class="section__subtitle section__subtitle--about">Self-Taught Engineer/Developer</p>

        <div class="about-me__body">
            <p>Hello my name is Steven Samera and I am a Filipino-American born in San Francisco.I am a fully knowledgeable, 
                committed and confident worker that always seeks to learn more and become better in whatever may be presented to me. I have a Google IT Support Specialist Certificate through 
                Coursera and now use my free time to learn how to code through FreeCodeCamp online. HTML, CSS, and Javascript is one of the courses I just recently completed.
                I'm still learning and enjoying everything that they have to offer through there, plus its free for anyone wanting to learn. My journey going into the tech field started when I 
                was put on furlough from my current job and while I had about almost four months of free time at home, I realized I wanted to pursue something different. Eager to know what kind of career 
                this may create for me and how much effort I need to put towards it, is what makes me passionate about learning more about it.</p>
        </div>

        <img class="image1" src="images/IMG_3469.jpg" alt="Cheers">

    </section>

    <!-- Work-->
    <section class="my-skills" id="skills">
        <h2 class="section__title--skills">Skills</h2>
        <p class="section__subtitle section__subtitle--skills">Logistics</p>

        <img id="skill-image" src="https://www.supplychainquarterly.com/ext/resources/2021/06/23/logistics-3125131_1920.jpg?t=1624536501&width=1080" alt="logistics">
                
        <br>
    <p class="section__subtitle section__subtitle--skills">IT Support</p>
    <img id="skill-image" src="images/Google IT Support Specialist Certificate.jpg" alt="IT Support">

    <p class="section__subtitle section__subtitle--skills">Security</p>
    <img id="skill-image" src="https://www.eldoradoinsurance.com/wp-content/uploads/2018/05/security-guard-services.jpg" alt="Security">

    
    </section>


    <!-- Footer -->
    <footer class="footer" id="contact">
        <a href="" class="footer__link">Stevehemp55@gmail.com</a>
        <ul class="social-list">
            <li class="social-list__item">
                <a class="social-list__link" href="https://www.linkedin.com/in/steven-samera-9b589b192/"><i class="fab fa-linkedin-in"></i>
                </a>
            </li>
            <li class="social-list__item">
                <a class="social-list__link" href="https://www.instagram.com/swole_steve/"><i class="fab fa-instagram"></i>
                </a>
            </li>
            <li class="social-list__item">
                <a class="social-list__link" href="https://www.facebook.com/steven.samera/"><i class="fab fa-facebook-square"></i>
                </a>
        </ul>
        



    </footer>

    <script src="js/index.js"></script>



</body>

    

</html>
