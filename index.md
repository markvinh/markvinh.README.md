## Welcome to GitHub Pages

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="assets/css/styles.css">
    <link rel="icon" href="/portfolio-responsive-complete-master/assets/img/MJ.ico">
    <!-- =====BOX ICONS===== -->
    <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>
    <!-- =====Font Awesome== -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Portfolio</title>
</head>

<body>
    <!--===== HEADER =====-->
    <header class="l-header">
        <nav class="nav bd-grid">
            <div>
                <a href="#home" class="nav__logo">Mark Vin Hufancia </a>
            </div>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                    <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                    <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                </ul>
            </div>

            <div class="nav__toggle" id="nav-toggle">
                <i class='bx bx-menu'></i>
            </div>
        </nav>
    </header>

    <main class="l-main">
        <!--===== HOME =====-->
        <section class="home bd-grid" id="home">

            <div class="home__data">
                <h1 class="home__title">Hi,<br>I'am <span class="home__title-color">Mark vin</span><br> Grade 11 student</h1>

                <a href="assets/resume/Update Resume.pdf Resume.pdf" class="button">Download Resume</a>
            </div>

            <div class="home__social">
                <a https://www.facebook.com/profile.php?id=100009101450761 a>
     	    </div>
	</section>

        <!--===== ABOUT =====-->
        <section class="about section " id="about">
            <h2 class="section-title">About</h2>

            <div class="about__container bd-grid">
                <div class="about__img">
                    <img src="assets/img/.jpg" alt="">
                </div>

                <div>
                    <h2 class="about__subtitle">I'am Mark Vin R. Hufancia</h2>
                    <p class="about__text">I'm Mark Vin R. Hufancia, they call me Mkvin. Grade 11 student pursuing my dream as ML player! </p>
                </div>
            </div>
        </section>

        <!--===== CONTACT =====-->
        <section class="contact section" id="contact">
            <h2 class="section-title">Contact Me</h2>

            <div class="contact__container bd-grid">
                <form action="" class="contact__form">
                    <!--  <input type="text" placeholder="Name" class="contact__input">
                    <input type="mail" placeholder="Email" class="contact__input">
                    <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>-->
                    <input type="button" value="Click Here!" class="contact__button button" onclick="location.href=https://drive.google.com/file/d/1oCcwzyVbWbJDN7G0mKNaVcz705JQ8Ffx/view?usp=sharing">

                </form>
            </div>
        </section>
    </main>


    <!--===== SCROLL REVEAL =====-->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!--===== MAIN JS =====-->
    <script src="assets/js/main.js"></script>
</body>

</html>
