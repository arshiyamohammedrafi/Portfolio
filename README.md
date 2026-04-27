# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
Home
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>Arshiya - Web Developer Portfolio</title>
  <meta name="description" content="Portfolio of Arshiya, an aspiring web developer showcasing projects and skills in HTML, CSS, JavaScript, and more.">
  <meta name="keywords" content="">

  <!-- Favicons -->
  <link href="assets/img/favicon.png" rel="icon">
  <link href="assets/img/apple-touch-icon.png" rel="apple-touch-icon">

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com" rel="preconnect">
  <link href="https://fonts.gstatic.com" rel="preconnect" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

  <!-- Vendor CSS Files -->
  <link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="assets/vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="assets/vendor/aos/aos.css" rel="stylesheet">
  <link href="assets/vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="assets/vendor/glightbox/css/glightbox.min.css" rel="stylesheet">

  <!-- Main CSS File -->
  <link href="assets/css/main.css" rel="stylesheet">

  <!-- =======================================================
  * Template Name: FolioOne
  * Template URL: https://bootstrapmade.com/folioone-bootstrap-portfolio-website-template/
  * Updated: Aug 23 2025 with Bootstrap v5.3.7
  * Author: BootstrapMade.com
  * License: https://bootstrapmade.com/license/
  ======================================================== -->
</head>

<body class="single-page">

  <header id="header" class="header d-flex align-items-center light-background sticky-top">
    <div class="container position-relative d-flex align-items-center justify-content-between">

      <!-- <a href="index.html" class="logo d-flex align-items-center me-auto me-xl-0">
      <img src="assets/img/logo.webp" alt="">
      <h1 class="sitename">FolioOne</h1> 
    </a> -->

      <nav id="navmenu" class="navmenu">
        <ul>
          <li><a href="#hero" >Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#portfolio">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
        <i class="mobile-nav-toggle d-xl-none bi bi-list"></i>
      </nav>

      <div class="header-social-links">
        <a href="#" class="twitter"><i class="bi bi-twitter-x"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
      </div>

    </div>
  </header>

  <main class="main">

    <!-- Hero Section -->
    <section id="hero" class="hero section">

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="row gy-4 align-items-center">
          <div class="col-lg-6 order-2 order-lg-1">
            <div class="hero-content">
              <h1 data-aos="fade-up" data-aos-delay="200">Hi, I'm <span class="highlight">Arshiya</span> 👋</h1>
              <p data-aos="fade-up" data-aos-delay="400" style="font-size: 1.25rem; line-height: 1.7;">I design and develop modern web applications that are fast, responsive, and user-centric. With a strong foundation in programming and a creative mindset, I turn ideas into functional digital experiences.</p>
              <div class="hero-actions" data-aos="fade-up" data-aos-delay="500">
                <a href="#portfolio" class="btn btn-primary">View My Work</a>
                <a href="#contact" class="btn btn-outline">Get In Touch</a>
              </div>
              <div class="social-links" data-aos="fade-up" data-aos-delay="600">
                <a href="#"><i class="bi bi-twitter"></i></a>
                <a href="https://www.linkedin.com/in/arshiya-m-7532a632a/" target="_blank" rel="noreferrer"><i class="bi bi-linkedin"></i></a>
                <a href="https://github.com/arshiyamohammedrafi" target="_blank" rel="noreferrer"><i class="bi bi-github"></i></a>
                <a href="#"><i class="bi bi-dribbble"></i></a>
              </div>
            </div>
          </div>
          <div class="col-lg-6 order-1 order-lg-2">
            <div class="hero-image" data-aos="zoom-in" data-aos-delay="300">
              <div class="image-wrapper">
                <img src="assets/img/mypic.jpeg" alt="Arshiya" class="img-fluid" style="max-width: 100%;">

                
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>

    </section><!-- /Hero Section -->

    <!-- About Section -->
    <section id="about" class="about section">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>About Me</h2>
        <p>I'm Arshiya — a passionate developer driven by curiosity, creativity, and a love for building meaningful digital experiences.</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <!-- Intro + Photo -->
        <div class="Intro">
          <div class="col-lg-7" data-aos="fade-right" data-aos-delay="150">
            <div class="intro-content" style="align-items: center;">
              
              <h2 class="headline">Hi, I'm Arshiya — a developer turning caffeine into code and ideas into reality.</h2>
              <p class="lead">
                My journey into tech started with a single question — how does this work? That curiosity never left. Today, it drives me to build web experiences that feel intuitive, look stunning, and perform flawlessly. I'm drawn to the creative side of development, where design thinking meets clean architecture, and where a great idea becomes something people actually love to use.
              </p>

              <div class="cta-group">
                <a href="#portfolio" class="btn-ghost">
                  View My Work <i class="bi bi-arrow-up-right"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
        <!-- End Intro + Photo -->
         <center>
              <h2>Skills</h2>
         </center>

        

        <!-- Skills Grid -->
        <div class="mb-5">
          <div class="row g-4">
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="120">
              <div class="skill-item">
                <i class="bi bi-code-slash"></i>
                <h3>Web Development</h3>
                <p>HTML, CSS, JavaScript</p>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="180">
              <div class="skill-item">
                <i class="bi bi-braces"></i>
                <h3>Programming</h3>
                <p>C,C++, Java, Python</p>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="240">
              <div class="skill-item">
                <i class="bi bi-server"></i>
                <h3>Database</h3>
                <p>SQL, Basics of DBMS</p>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="300">
              <div class="skill-item">
                <i class="bi bi-github"></i>
                <h3>Tools</h3>
                <p>Git, VS Code, Figma,Canva</p>
              </div>
            </div>
          </div>
        </div>
        <!-- End Skills Grid -->

        
        
<center>
<h2>Hobbies</h2>
</center>
        

        <!-- Fun Facts -->
        <div class="row g-3 justify-content-center">
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="120">
            <div class="fact-pill">
              <i class="bi bi-laptop"></i>
              <span>Coding</span>
            </div>
          </div>
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="160">
            <div class="fact-pill">
              <i class="bi bi-book"></i>
              <span>Reading</span>
            </div>
          </div>
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="200">
            <div class="fact-pill">
              <i class="bi bi-controller"></i>
              <span>Gaming</span>
            </div>
          </div>
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="240">
            <div class="fact-pill">
              <i class="bi bi-cup-hot"></i>
              <span>Coffee</span>
            </div>
          </div>
        </div>
        <!-- End Fun Facts -->

      </div>

    </section><!-- /About Section -->

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio section">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Projects</h2>
        <p>Here are some of my academic and personal projects as an engineering student.</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="isotope-layout" data-default-filter="*" data-layout="masonry" data-sort="original-order">
          <ul class="portfolio-filters isotope-filters" data-aos="fade-up" data-aos-delay="200">
            <li data-filter="*" class="filter-active">All</li>
            <li data-filter=".filter-web">Web</li>
            <li data-filter=".filter-app">Software</li>
            <li data-filter=".filter-other">Other</li>
          </ul><!-- End Portfolio Filters -->

```
About
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>About - FolioOne Bootstrap Template</title>
  <meta name="description" content="">
  <meta name="keywords" content="">

  <!-- Favicons -->
  <link href="assets/img/favicon.png" rel="icon">
  <link href="assets/img/apple-touch-icon.png" rel="apple-touch-icon">

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com" rel="preconnect">
  <link href="https://fonts.gstatic.com" rel="preconnect" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

  <!-- Vendor CSS Files -->
  <link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="assets/vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="assets/vendor/aos/aos.css" rel="stylesheet">
  <link href="assets/vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="assets/vendor/glightbox/css/glightbox.min.css" rel="stylesheet">

  <!-- Main CSS File -->
  <link href="assets/css/main.css" rel="stylesheet">

  
</head>

<body class="about-page">

  <header id="header" class="header d-flex align-items-center light-background sticky-top">
    <div class="container position-relative d-flex align-items-center justify-content-between">

      <!-- <a href="index.html" class="logo d-flex align-items-center me-auto me-xl-0">
      <img src="assets/img/logo.webp" alt="">
      <h1 class="sitename">FolioOne</h1> 
    </a> -->

      <nav id="navmenu" class="navmenu">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="about.html" class="active">About</a></li>
          <li><a href="projects.html">Projects</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
        <i class="mobile-nav-toggle d-xl-none bi bi-list"></i>
      </nav>

      <div class="header-social-links">
        <a href="#" class="twitter"><i class="bi bi-twitter-x"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
      </div>

    </div>
  </header>

  <main class="main">

    <!-- About Section -->
    <section id="about" class="about section">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>About Me</h2>
        <p>I'm Arshiya — a passionate developer driven by curiosity, creativity, and a love for building meaningful digital experiences.</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <!-- Intro + Photo -->
        <div class="row align-items-center justify-content-center gy-5 mb-5">
          <div class="col-lg-7" data-aos="fade-right" data-aos-delay="150">
            <div class="intro-content">
              
              
              <h2 class="headline">I'm passionate about crafting digital experiences that are not just functional, but genuinely delightful. My work sits at the intersection of logic and design — where clean code meets thoughtful UI.</h2>
        
              <p class="lead">
                My journey into tech started with a single question — how does this work? That curiosity never left. Today, it drives me to build web experiences that feel intuitive, look stunning, and perform flawlessly. I'm drawn to the creative side of development, where design thinking meets clean architecture, and where a great idea becomes something people actually love to use.
              </p>
             

            <div class="cta-group">
                <a href="projects.html" class="btn-ghost">
                  View My Work <i class="bi bi-arrow-up-right"></i>
                </a>
              </div>
            </div>
          </div>

         
        </div>
        <!-- End Intro + Photo -->

        <!-- Skills Grid -->
        <div class="mb-5">
          <div class="row g-4">
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="120">
              <div class="skill-item">
                <i class="bi bi-code-slash"></i>
                <h3>Web Development</h3>
                <p>HTML, CSS, JavaScript</p>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="180">
              <div class="skill-item">
                <i class="bi bi-braces"></i>
                <h3>Programming</h3>
                <p>C,C++, Java, Python</p>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="240">
              <div class="skill-item">
                <i class="bi bi-server"></i>
                <h3>Database</h3>
                <p>SQL, Basics of DBMS</p>
              </div>
            </div>
            <div class="col-6 col-md-4 col-lg-3" data-aos="fade-up" data-aos-delay="300">
              <div class="skill-item">
                <i class="bi bi-github"></i>
                <h3>Tools</h3>
                <p>Git, VS Code, Figma, Canva</p>
              </div>
            </div>
          </div>
        </div>
        <!-- End Skills Grid -->

        

        

        <!-- Fun Facts -->
        <div class="row g-3 justify-content-center">
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="120">
            <div class="fact-pill">
              <i class="bi bi-laptop"></i>
              <span>Coding</span>
            </div>
          </div>
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="160">
            <div class="fact-pill">
              <i class="bi bi-book"></i>
              <span>Reading</span>
            </div>
          </div>
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="200">
            <div class="fact-pill">
              <i class="bi bi-controller"></i>
              <span>Gaming</span>
            </div>
          </div>
          <div class="col-6 col-md-3 col-lg-2" data-aos="zoom-in" data-aos-delay="240">
            <div class="fact-pill">
              <i class="bi bi-cup-hot"></i>
              <span>Coffee</span>
            </div>
          </div>
        </div>
        <!-- End Fun Facts -->

      </div>

    </section><!-- /About Section -->



  </main>

  <footer id="footer" class="footer">

    <div class="container">
      <div class="copyright text-center ">
        <p>© <span>Copyright</span> <strong class="px-1 sitename">FolioOne</strong> <span>All Rights Reserved<br></span></p>
      </div>
      <div class="social-links d-flex justify-content-center">
        <a href=""><i class="bi bi-twitter-x"></i></a>
        <a href=""><i class="bi bi-facebook"></i></a>
        <a href=""><i class="bi bi-instagram"></i></a>
        <a href=""><i class="bi bi-linkedin"></i></a>
      </div>
      <div class="credits">
        <!-- All the links in the footer should remain intact. -->
        <!-- You can delete the links only if you've purchased the pro version. -->
        <!-- Licensing information: https://bootstrapmade.com/license/ -->
        <!-- Purchase the pro version with working PHP/AJAX contact form: [buy-url] -->
        Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a> | <a href="https://bootstrapmade.com/tools/">DevTools</a>
      </div>
    </div>

  </footer>

  <!-- Scroll Top -->
  <a href="#" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>

  <!-- Preloader removed to prevent infinite loading -->

  <!-- Vendor JS Files -->
  <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/vendor/php-email-form/validate.js"></script>
  <script src="assets/vendor/aos/aos.js"></script>
  <script src="assets/vendor/typed.js/typed.umd.js"></script>
  <script src="assets/vendor/waypoints/noframework.waypoints.js"></script>
  <script src="assets/vendor/purecounter/purecounter_vanilla.js"></script>
  <script src="assets/vendor/swiper/swiper-bundle.min.js"></script>
  <script src="assets/vendor/imagesloaded/imagesloaded.pkgd.min.js"></script>
  <script src="assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
  <script src="assets/vendor/glightbox/js/glightbox.min.js"></script>

  <!-- Main JS File -->
  <script src="assets/js/main.js"></script>

</body>

</html>
```
Projects
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>Projects - Arshiya Web Developer</title>
  <meta name="description" content="Projects by Arshiya">
  <meta name="keywords" content="">

  <!-- Favicons -->
  <link href="assets/img/favicon.png" rel="icon">
  <link href="assets/img/apple-touch-icon.png" rel="apple-touch-icon">

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com" rel="preconnect">
  <link href="https://fonts.gstatic.com" rel="preconnect" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

  <!-- Vendor CSS Files -->
  <link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="assets/vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="assets/vendor/aos/aos.css" rel="stylesheet">
  <link href="assets/vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="assets/vendor/glightbox/css/glightbox.min.css" rel="stylesheet">

  <!-- Main CSS File -->
  <link href="assets/css/main.css" rel="stylesheet">
</head>

<body class="portfolio-page">

  <header id="header" class="header d-flex align-items-center light-background sticky-top">
    <div class="container position-relative d-flex align-items-center justify-content-between">
      <nav id="navmenu" class="navmenu">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="projects.html" class="active">Projects</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
        <i class="mobile-nav-toggle d-xl-none bi bi-list"></i>
      </nav>

      <div class="header-social-links">
        <a href="#" class="twitter"><i class="bi bi-twitter-x"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
      </div>
    </div>
  </header>

  <main class="main">

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio section">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Projects</h2>
        <p>Here are some of my academic and personal projects as an engineering student.</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="isotope-layout" data-default-filter="*" data-layout="masonry" data-sort="original-order">
          <ul class="portfolio-filters isotope-filters" data-aos="fade-up" data-aos-delay="200">
            <li data-filter="*" class="filter-active">All</li>
            <li data-filter=".filter-web">Web</li>
            <li data-filter=".filter-app">Software</li>
            <li data-filter=".filter-other">Other</li>
          </ul><!-- End Portfolio Filters -->

          <div class="row gy-4 isotope-container" data-aos="fade-up" data-aos-delay="300">
            <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-web">
              <div class="portfolio-card">
                <div class="portfolio-img">
                  <img src="assets/img/PORTFOLIO.PNG" alt="Portfolio Website" class="img-fluid">
                  <div class="portfolio-overlay">
                    <a href="assets/img/PORTFOLIO.PNG" class="glightbox portfolio-lightbox"><i class="bi bi-plus"></i></a>
                    <a href="#" class="portfolio-details-link"><i class="bi bi-link"></i></a>
                  </div>
                </div>
                <div class="portfolio-info">
                  <h4>Portfolio Website</h4>
                  <p>Clean portfolio UI built with HTML, CSS, and JavaScript.</p>
                  <div class="portfolio-tags">
                    <span>Web</span>
                    <span>Frontend</span>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-web">
              <div class="portfolio-card">
                <div class="portfolio-img">
                  <img src="assets/img/TODO.PNG" alt="Todo List App" class="img-fluid">
                  <div class="portfolio-overlay">
                    <a href="assets/img/TODO.PNG" class="glightbox portfolio-lightbox"><i class="bi bi-plus"></i></a>
                    <a href="#" class="portfolio-details-link"><i class="bi bi-link"></i></a>
                  </div>
                </div>
                <div class="portfolio-info">
                  <h4>Todo List App</h4>
                  <p>Interactive task manager with JavaScript and local storage.</p>
                  <div class="portfolio-tags">
                    <span>Web</span>
                    <span>JavaScript</span>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-web">
              <div class="portfolio-card">
                <div class="portfolio-img">
                  <img src="assets/img/ECOMMERCE.PNG" alt="E-commerce UI" class="img-fluid">
                  <div class="portfolio-overlay">
                    <a href="assets/img/ECOMMERCE.PNG" class="glightbox portfolio-lightbox"><i class="bi bi-plus"></i></a>
                    <a href="#" class="portfolio-details-link"><i class="bi bi-link"></i></a>
                  </div>
                </div>
                <div class="portfolio-info">
                  <h4>E-commerce UI</h4>
                  <p>Modern product listing layout with responsive design.</p>
                  <div class="portfolio-tags">
                    <span>Web</span>
                    <span>Design</span>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-app">
              <div class="portfolio-card">
                <div class="portfolio-img">
                  <img src="assets/img/DASHBOARD.PNG" alt="Student Dashboard" class="img-fluid">
                  <div class="portfolio-overlay">
                    <a href="assets/img/DASHBOARD.PNG" class="glightbox portfolio-lightbox"><i class="bi bi-plus"></i></a>
                    <a href="#" class="portfolio-details-link"><i class="bi bi-link"></i></a>
                  </div>
                </div>
                <div class="portfolio-info">
                  <h4>Student Dashboard</h4>
                  <p>A dashboard layout for student progress and analytics.</p>
                  <div class="portfolio-tags">
                    <span>Software</span>
                    <span>Backend</span>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-other">
              <div class="portfolio-card">
                <div class="portfolio-img">
                  <img src="assets/img/weather.png" alt="Weather App" class="img-fluid">
                  <div class="portfolio-overlay">
                    <a href="assets/img/weather.png" class="glightbox portfolio-lightbox"><i class="bi bi-plus"></i></a>
                    <a href="#" class="portfolio-details-link"><i class="bi bi-link"></i></a>
                  </div>
                </div>
                <div class="portfolio-info">
                  <h4>Weather App</h4>
                  <p>Simple weather dashboard using API integration.</p>
                  <div class="portfolio-tags">
                    <span>Other</span>
                    <span>API</span>
                  </div>
                </div>
              </div>
            </div>

          </div><!-- End Portfolio Container -->

        </div>

      </div>

    </section><!-- /Portfolio Section -->

  </main>

  <footer id="footer" class="footer">
    <div class="container">
      <div class="copyright text-center ">
        <p>© <span>Copyright</span> <strong class="px-1 sitename">Arshiya</strong> <span>All Rights Reserved<br></span></p>
      </div>
      <div class="social-links d-flex justify-content-center">
        <a href=""><i class="bi bi-twitter-x"></i></a>
        <a href=""><i class="bi bi-facebook"></i></a>
        <a href=""><i class="bi bi-instagram"></i></a>
        <a href=""><i class="bi bi-linkedin"></i></a>
      </div>
    </div>
  </footer>

  <!-- Scroll Top -->
  <a href="#" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>

  <!-- Preloader -->
  <div id="preloader"></div>

  <!-- Vendor JS Files -->
  <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/vendor/php-email-form/validate.js"></script>
  <script src="assets/vendor/aos/aos.js"></script>
  <script src="assets/vendor/typed.js/typed.umd.js"></script>
  <script src="assets/vendor/waypoints/noframework.waypoints.js"></script>
  <script src="assets/vendor/purecounter/purecounter_vanilla.js"></script>
  <script src="assets/vendor/swiper/swiper-bundle.min.js"></script>
  <script src="assets/vendor/imagesloaded/imagesloaded.pkgd.min.js"></script>
  <script src="assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
  <script src="assets/vendor/glightbox/js/glightbox.min.js"></script>

  <!-- Main JS File -->
  <script src="assets/js/main.js"></script>

</body>

</html>

```
Contact
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>Contact - Arshiya Web Developer</title>
  <meta name="description" content="">
  <meta name="keywords" content="">

  <!-- Favicons -->
  <link href="assets/img/favicon.png" rel="icon">
  <link href="assets/img/apple-touch-icon.png" rel="apple-touch-icon">

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com" rel="preconnect">
  <link href="https://fonts.gstatic.com" rel="preconnect" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

  <!-- Vendor CSS Files -->
  <link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="assets/vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="assets/vendor/aos/aos.css" rel="stylesheet">
  <link href="assets/vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="assets/vendor/glightbox/css/glightbox.min.css" rel="stylesheet">

  <!-- Main CSS File -->
  <link href="assets/css/main.css" rel="stylesheet">

  <!-- =======================================================
  * Template Name: FolioOne
  * Template URL: https://bootstrapmade.com/folioone-bootstrap-portfolio-website-template/
  * Updated: Aug 23 2025 with Bootstrap v5.3.7
  * Author: BootstrapMade.com
  * License: https://bootstrapmade.com/license/
  ======================================================== -->
</head>

<body class="contact-page">

  <header id="header" class="header d-flex align-items-center light-background sticky-top">
    <div class="container position-relative d-flex align-items-center justify-content-between">

      <!-- <a href="index.html" class="logo d-flex align-items-center me-auto me-xl-0">
      <img src="assets/img/logo.webp" alt="">
      <h1 class="sitename">FolioOne</h1> 
    </a> -->

      <nav id="navmenu" class="navmenu">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="projects.html">Projects</a></li>
          <li><a href="contact.html" class="active">Contact</a></li>
        </ul>
        <i class="mobile-nav-toggle d-xl-none bi bi-list"></i>
      </nav>

      <div class="header-social-links">
        <a href="#" class="twitter"><i class="bi bi-twitter-x"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
      </div>

    </div>
  </header>

  <main class="main">

    <!-- Contact Section -->
    <section id="contact" class="contact section">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Contact</h2>
        <p>Let's connect! Feel free to reach out for collaborations or just to say hello.</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="row g-4 g-lg-5">
          <div class="col-lg-5">
            <div class="info-box" data-aos="fade-up" data-aos-delay="200">
              <h3>Contact Info</h3>
              <p>I'm always interested in new opportunities and connecting with fellow developers.</p>

              <div class="info-item" data-aos="fade-up" data-aos-delay="300">
                <div class="icon-box">
                  <i class="bi bi-envelope"></i>
                </div>
                <div class="content">
                  <h4>Email</h4>
                  <p>arshiya@example.com</p>
                </div>
              </div>

              <div class="info-item" data-aos="fade-up" data-aos-delay="400">
                <div class="icon-box">
                  <i class="bi bi-linkedin"></i>
                </div>
                <div class="content">
                  <h4>LinkedIn</h4>
                  <p>linkedin.com/in/arshiya</p>
                </div>
              </div>

              <div class="info-item" data-aos="fade-up" data-aos-delay="500">
                <div class="icon-box">
                  <i class="bi bi-github"></i>
                </div>
                <div class="content">
                  <h4>GitHub</h4>
                  <p>github.com/arshiya</p>
                </div>
              </div>
            </div>
          </div>

          <div class="col-lg-7">
            <div class="contact-form" data-aos="fade-up" data-aos-delay="300">
              <h3>Send Message</h3>
              <p>Have a project in mind or just want to chat? Drop me a message!</p>

              <form action="forms/contact.php" method="post" class="php-email-form" data-aos="fade-up" data-aos-delay="200">
                <div class="row gy-4">

                  <div class="col-md-6">
                    <input type="text" name="name" class="form-control" placeholder="Your Name" required="">
                  </div>

                  <div class="col-md-6 ">
                    <input type="email" class="form-control" name="email" placeholder="Your Email" required="">
                  </div>

                  <div class="col-12">
                    <input type="text" class="form-control" name="subject" placeholder="Subject" required="">
                  </div>

                  <div class="col-12">
                    <textarea class="form-control" name="message" rows="6" placeholder="Message" required=""></textarea>
                  </div>

                  <div class="col-12 text-center">
                    <div class="loading">Loading</div>
                    <div class="error-message"></div>
                    <div class="sent-message">Your message has been sent. Thank you!</div>

                    <button type="submit" class="btn">Send Message</button>
                  </div>

                </div>
              </form>

            </div>
          </div>

        </div>

      </div>

    </section><!-- /Contact Section -->

  </main>

  <footer id="footer" class="footer">

    <div class="container">
      <div class="copyright text-center ">
        <p>© <span>Copyright</span> <strong class="px-1 sitename">FolioOne</strong> <span>All Rights Reserved<br></span></p>
      </div>
      <div class="social-links d-flex justify-content-center">
        <a href=""><i class="bi bi-twitter-x"></i></a>
        <a href=""><i class="bi bi-facebook"></i></a>
        <a href=""><i class="bi bi-instagram"></i></a>
        <a href=""><i class="bi bi-linkedin"></i></a>
      </div>
      <div class="credits">
        <!-- All the links in the footer should remain intact. -->
        <!-- You can delete the links only if you've purchased the pro version. -->
        <!-- Licensing information: https://bootstrapmade.com/license/ -->
        <!-- Purchase the pro version with working PHP/AJAX contact form: [buy-url] -->
        Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a> | <a href="https://bootstrapmade.com/tools/">DevTools</a>
      </div>
    </div>

  </footer>

  <!-- Scroll Top -->
  <a href="#" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>

  <!-- Preloader -->
  <div id="preloader"></div>

  <!-- Vendor JS Files -->
  <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/vendor/php-email-form/validate.js"></script>
  <script src="assets/vendor/aos/aos.js"></script>
  <script src="assets/vendor/typed.js/typed.umd.js"></script>
  <script src="assets/vendor/waypoints/noframework.waypoints.js"></script>
  <script src="assets/vendor/purecounter/purecounter_vanilla.js"></script>
  <script src="assets/vendor/swiper/swiper-bundle.min.js"></script>
  <script src="assets/vendor/imagesloaded/imagesloaded.pkgd.min.js"></script>
  <script src="assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
  <script src="assets/vendor/glightbox/js/glightbox.min.js"></script>

  <!-- Main JS File -->
  <script src="assets/js/main.js"></script>

</body>

</html>
```




## OUTPUT
<img width="1816" height="910" alt="image" src="https://github.com/user-attachments/assets/c3946876-5f60-432a-87de-9591fea6de6e" />

<img width="1846" height="904" alt="image" src="https://github.com/user-attachments/assets/7a3e616a-8ffe-4fb3-b011-a26c50bc9545" />

<img width="1819" height="514" alt="image" src="https://github.com/user-attachments/assets/a36ff696-63cc-4a96-ad01-8ad9dbf18db9" />

<img width="1899" height="913" alt="image" src="https://github.com/user-attachments/assets/66af5b64-5c75-4262-ba43-56b4aed1d5a9" />

<img width="1873" height="926" alt="image" src="https://github.com/user-attachments/assets/b9c5e8fc-52c8-4b03-b333-c10b161db552" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
