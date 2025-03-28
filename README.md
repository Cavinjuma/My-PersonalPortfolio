# My-PersonalPortfolio


<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Juma - Personal Portfolio</title>

  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="./assets/images/logo.ico" type="image/x-icon">

  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">
  <script src="script.js"></script>
  <script>  
document.addEventListener("DOMContentLoaded", function() {
  alert("Welcome to My Personal Portfolio!");
 
});

function toggleFAQ(faqID) {
  let answer = document.getElementById(faqID);
  answer.style.display = answer.style.display === "none" ? "block" : "none";
}

  </script>

  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>

<body>

  <!--
    - #MAIN
  -->

  <main>

    <!--
      - #SIDEBAR
    -->

    <aside class="sidebar" data-sidebar>

      <div class="sidebar-info">

        <figure class="avatar-box">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTRfMGOOrTOcdoZbHMk7j9IeIQa2xSYtCaojg&s" alt="Juma Cavin" width="80">
        </figure>

        <div class="info-content">
          <h1 class="name" title="Juma Cavin">Juma Cavin Otieno</h1>

          <p class="title">Web developer</p>
        </div>

        <button class="info_more-btn" data-sidebar-btn>
          <span>Show Contacts</span>

          <ion-icon name="chevron-down"></ion-icon>
        </button>

      </div>

      <div class="sidebar-info_more">

        <div class="separator"></div>

        <ul class="contacts-list">

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Email</p>

              <a href="mailto:juma@example.com" class="contact-link">juma@example.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Phone</p>

              <a href="tel:+254704225571" class="contact-link">0704225571</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Birthday</p>

              <time datetime="2003-02-23">February 23,2003</time>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Location</p>

              <address>Ruiru, Kiambu, Kenya</address>
            </div>

          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">

          <li class="social-item">
            <a href="#" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="#" class="social-link">
              <ion-icon name="logo-twitter"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="#" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

        </ul>

      </div>

    </aside>





    <!--
      - #main-content
    -->

    <div class="main-content">

      <!--
        - #NAVBAR
      -->

      <nav class="navbar">

        <ul class="navbar-list">

          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Portfolio</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Future</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li>

        </ul>

      </nav>





      <!--
        - #ABOUT
      -->

      <article class="about  active" data-page="about">

        <header>
          <h2 class="h2 article-title">About Juma</h2>
        </header>

        <section class="about-text">
          <p>
            I'm a student and a Software Engineer from Nairobi,Kenya, working in web development.
            I enjoy
              turning complex problems into simple, beautiful and intuitive designs.
          </p>

          <p>
            My job is to build your website so that it is functional and user-friendly but at the same time attractive.
            Moreover, I
            add personal touch to your product and make sure that is eye-catching and easy to use. My aim is to bring
            across your
            message and identity in the most creative way. I created web design for many famous brand companies.
          </p>
        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">What I do...</h3>

          <ul class="service-list">

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-design.svg
                " alt="design icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web design</h4>

                <p class="service-item-text">
                  The most modern and high-quality design made at an intermediate level.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-dev.svg" alt="Web development icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web development</h4>

                <p class="service-item-text">
                  High-quality development of sites at the professional level.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Mobile apps</h4>

                <p class="service-item-text">
                  Professional development of Android applications.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="camera icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Photography</h4>

                <p class="service-item-text">
                  I capture high-quality photos for events and any other category at a professional level. 
                </p>
              </div>

            </li>

          </ul>

        </section>


        <!--
          - testimonials
        -->

        <section class="testimonials">

          <h3 class="h3 testimonials-title">Testimonials</h3>

          <ul class="testimonials-list has-scrollbar">

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="data:image/jpeg;base64,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" alt="Daniel lewis" width="60" height="80">
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Daniel Kipkorir</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Juma was hired to create a corporate identity. We were very pleased with the work done. He has a
                    lot of experience
                    and is very concerned about the needs of client. Good work,Juma.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="data:image/jpeg;base64,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" alt="Jessica Wamae Njogu" width="60" height="80">
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Jessica Wamae Njogu</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Juma was hired to create a corporate identity. We were very pleased with the work done. He has a
                    lot of experience
                    and is very concerned about the needs of client. Good work,Juma.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQ1Kn1ablidDtMlhmWA9ZikLBoIa0pUjsHAA&s" alt="Emily Atieno" width="60"height="80">
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Emily Atieno</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Juma was hired to create a corporate identity. We were very pleased with the work done. he has a
                    lot of experience
                    and is very concerned about the needs of client. Good work,Juma.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREs7dz9pfSVIFCQwZrR7iXKweaqNYPAHmecw&s" alt="Abdul William" width="60" height="80">
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Abdul William</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Juma was hired to create a corporate identity. We were very pleased with the work done. he has a
                    lot of experience
                    and is very concerned about the needs of client. Good work,Juma.
                  </p>
                </div>

              </div>
            </li>

          </ul>

        </section>


        <!--
          - testimonials modal
        -->

        <div class="modal-container" data-modal-container>

          <div class="overlay" data-overlay></div>

          <section class="testimonials-modal">

            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>

            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
              </figure>

              <img src="./assets/images/icon-quote.svg" alt="quote icon">
            </div>

            <div class="modal-content">

              <h4 class="h3 modal-title" data-modal-title>Daniel Kipkorir</h4>

              <time datetime="2021-06-14">14 June, 2021</time>

              <div data-modal-text>
                <p>
                  Juma was hired to create a corporate identity. We were very pleased with the work done. he has a
                  lot of experience
                  and is very concerned about the needs of client. Good work,Juma.
                </p>
              </div>

            </div>

          </section>

        </div>


        <!--
          - clients
        -->

        <section class="clients">

          <h3 class="h3 clients-title">Clients</h3>

          <ul class="clients-list has-scrollbar">

            <li class="clients-item">
              <a href="#">
                <img src="data:image/png;base64,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" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="data:image/png;base64,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" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="data:image/png;base64,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" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="data:image/png;base64,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" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="data:image/jpeg;base64,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" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="data:image/jpeg;base64,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" alt="client logo">
              </a>
            </li>

          </ul>

        </section>

      </article>





      <!--
        - #RESUME
      -->

      <article class="resume" data-page="resume">

        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Zetech University</h4>

              <span>2022-2025</span>

              <p class="timeline-text">Studied Bachelors of science in Software Engineering
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">PowerLearn Project Schorlaship</h4>

              <span>2024-2025</span>

              <p class="timeline-text">I was a benefitiary of this fully sponsored Schorlaship opportunity due to my competetive skillset
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">High school</h4>

              <span>2018 — 2021</span>

              <p class="timeline-text">Studied in a county school, Kisumu Boys School situated in Kisumu City, Kenya.
              </p>

            </li>

          </ol>

        </section>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Experience</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Casino Dealer</h4>

              <span>2024 — Present</span>

              <p class="timeline-text">Gained employment as a Casino dealer due to my exquisite PR.
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Web Developer</h4>

              <span>2023 — Present</span>

              <p class="timeline-text">Work remotely as a Software Engineer, specifically web development.
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Photography</h4>

              <span>2020 — 2024</span>

              <p class="timeline-text">Worked as a self employed professional photogragher.
              </p>

            </li>

          </ol>

        </section>

        <section class="skill">

          <h3 class="h3 skills-title">My skills</h3>

          <ul class="skills-list content-card">

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Web development</h5>
                <data value="80">80%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 80%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Graphic design</h5>
                <data value="70">70%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Branding</h5>
                <data value="90">90%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">WordPress</h5>
                <data value="50">50%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div>

            </li>

            
            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Photography</h5>
                <data value="75">75%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 75%;"></div>
              </div>

            </li>
          </ul>

        </section>

      </article>





      <!--
        - #PORTFOLIO
      -->

      <article class="portfolio" data-page="portfolio">

        <header>
          <h2 class="h2 article-title">Portfolio</h2>
        </header>

        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn>All</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Web design</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Applications</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Web development</button>
            </li>

          </ul>

          <div class="filter-select-box">

            <button class="filter-select" data-select>

              <div class="select-value" data-selecct-value>Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item>All</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web design</button>
              </li>

              <li class="select-item">
                <button data-select-item>Applications</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web development</button>
              </li>

            </ul>

          </div>

          <ul class="project-list">

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-1.jpg" alt="finance" loading="lazy">
                </figure>

                <h3 class="project-title">Finance</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-2.png" alt="airtel" loading="lazy">
                </figure>

                <h3 class="project-title">Airtel</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="data:image/jpeg;base64,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" alt="Zetech" loading="lazy">
                </figure>

                <h3 class="project-title">Zetech Uni</h3>

                <p class="project-category">Web design</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-4.png" alt="Abno" loading="lazy">
                </figure>

                <h3 class="project-title">Abno Softwares</h3>

                <p class="project-category">Applications</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-5.png" alt="dsm." loading="lazy">
                </figure>

                <h3 class="project-title">DSM.</h3>

                <p class="project-category">Web design</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-6.png" alt="metaspark" loading="lazy">
                </figure>

                <h3 class="project-title">MetaSpark</h3>

                <p class="project-category">Web design</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-7.png" alt="summary" loading="lazy">
                </figure>

                <h3 class="project-title">Summary</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-8.jpg" alt="task manager" loading="lazy">
                </figure>

                <h3 class="project-title">Task Manager</h3>

                <p class="project-category">Applications</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-9.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Arrival</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

          </ul>

        </section>

      </article>






<!-- Future
  Aspirations Page -->

<head>
   <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        text-align: center;
        background-color: #f4f4f4;
    }
    header {
        background: #333;
        color: white;
        padding: 15px;
    }
    nav ul {
        list-style: none;
        padding: 0;
    }
    nav ul li {
        display: inline;
        margin: 0 15px;
    }
    nav ul li a {
        color: white;
        text-decoration: none;
    }
    main {
        padding: 20px;
    }
    button {
        padding: 10px 15px;
        background: #007bff;
        color: white;
        border: none;
        cursor: pointer;
    }
    </style>

</head>
  <article class="future" data-page="future">

    <header>
      <h2 class="h2 article-title">Future</h2>
    </header>

    <section class="future-posts">

      <h2>My Goals & Dreams</h2>
      <p>I aspire to achieve great things in my career and personal life. My goals include:</p>
      <ul>
        <br>
          <li>Becoming a successful professional Software Engineer.</li>
          <li>Continuing to learn and improve my skills in this field.</li>
          <li>Contributing to society through meaningful work.</li>
          <li>Traveling the world and experiencing different cultures.</li>
      </ul>
      <button id="motivateButton">Click for Motivation</button>
      <p id="motivationText"></p>


    </section>
    <br><br>
    <footer>
      <p>&copy; 2025 My Personal Website. All rights reserved.</p>
  </footer>

  </article>
      <!--
        - #CONTACT
      -->

      <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>


        <section class="contact-form">

          <h3 class="h3 form-title">Contact Form</h3>

          <p>Contact me by filling this contact form</p>

          <form action="#" class="form" data-form>

            <div class="input-wrapper">
              <input type="text" name="fullname" class="form-input" placeholder="Full name" required data-form-input>

              <input type="email" name="email" class="form-input" placeholder="Email address" required data-form-input>
            </div>

            <textarea name="message" class="form-input" placeholder="Your Message" required data-form-input></textarea>

            <button class="form-btn" type="submit" disabled data-form-btn>
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>
              <p><b>THANK YOU</b></p>
          </form>

        </section>

      </article>

    </div>

  </main>






  <!--
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>




#Style.css code



:root {

  /**
   * colors
   */

  /* gradient */

  --bg-gradient-onyx: linear-gradient(
    to bottom right, 
    hsl(240, 1%, 25%) 3%, 
    hsl(0, 0%, 19%) 97%
  );
  --bg-gradient-jet: linear-gradient(
    to bottom right, 
    hsla(240, 1%, 18%, 0.251) 0%, 
    hsla(240, 2%, 11%, 0) 100%
  ), hsl(240, 2%, 13%);
  --bg-gradient-yellow-1: linear-gradient(
    to bottom right, 
    hsl(45, 100%, 71%) 0%, 
    hsla(36, 100%, 69%, 0) 50%
  );
  --bg-gradient-yellow-2: linear-gradient(
    135deg, 
    hsla(45, 100%, 71%, 0.251) 0%, 
    hsla(35, 100%, 68%, 0) 59.86%
  ), hsl(240, 2%, 13%);
  --border-gradient-onyx: linear-gradient(
    to bottom right, 
    hsl(0, 0%, 25%) 0%, 
    hsla(0, 0%, 25%, 0) 50%
  );
  --text-gradient-yellow: linear-gradient(
    to right, 
    hsl(45, 100%, 72%), 
    hsl(35, 100%, 68%)
  );

  /* solid */

  --jet: hsl(0, 0%, 22%);
  --onyx: hsl(240, 1%, 17%);
  --eerie-black-1: hsl(240, 2%, 13%);
  --eerie-black-2: hsl(240, 2%, 12%);
  --smoky-black: hsl(0, 0%, 7%);
  --white-1: hsl(0, 0%, 100%);
  --white-2: hsl(0, 0%, 98%);
  --orange-yellow-crayola: hsl(45, 100%, 72%);
  --vegas-gold: hsl(45, 54%, 58%);
  --light-gray: hsl(0, 0%, 84%);
  --light-gray-70: hsla(0, 0%, 84%, 0.7);
  --bittersweet-shimmer: hsl(0, 43%, 51%);

  /**
   * typography
   */

  /* font-family */
  --ff-poppins: 'Poppins', sans-serif;

  /* font-size */
  --fs-1: 24px;
  --fs-2: 18px;
  --fs-3: 17px;
  --fs-4: 16px;
  --fs-5: 15px;
  --fs-6: 14px;
  --fs-7: 13px;
  --fs-8: 11px;

  /* font-weight */
  --fw-300: 300;
  --fw-400: 400;
  --fw-500: 500;
  --fw-600: 600;

  /**
   * shadow
   */
  
  --shadow-1: -4px 8px 24px hsla(0, 0%, 0%, 0.25);
  --shadow-2: 0 16px 30px hsla(0, 0%, 0%, 0.25);
  --shadow-3: 0 16px 40px hsla(0, 0%, 0%, 0.25);
  --shadow-4: 0 25px 50px hsla(0, 0%, 0%, 0.15);
  --shadow-5: 0 24px 80px hsla(0, 0%, 0%, 0.25);

  /**
   * transition
   */

  --transition-1: 0.25s ease;
  --transition-2: 0.5s ease-in-out;

}





/*-----------------------------------*\
  #RESET
\*-----------------------------------*/

*, *::before, *::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

a { text-decoration: none; }

li { list-style: none; }

img, ion-icon, a, button, time, span { display: block; }

button {
  font: inherit;
  background: none;
  border: none;
  text-align: left;
  cursor: pointer;
}

input, textarea {
  display: block;
  width: 100%;
  background: none;
  font: inherit;
}

::selection {
  background: var(--orange-yellow-crayola);
  color: var(--smoky-black);
}

:focus { outline-color: var(--orange-yellow-crayola); }

html { font-family: var(--ff-poppins); }

body { background: var(--smoky-black); }





/*-----------------------------------*\
  #REUSED STYLE
\*-----------------------------------*/

.sidebar,
article {
  background: var(--eerie-black-2);
  border: 1px solid var(--jet);
  border-radius: 20px;
  padding: 15px;
  box-shadow: var(--shadow-1);
  z-index: 1;
}

.separator {
  width: 100%;
  height: 1px;
  background: var(--jet);
  margin: 16px 0;
}

.icon-box {
  position: relative;
  background: var(--border-gradient-onyx);
  width: 30px;
  height: 30px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 16px;
  color: var(--orange-yellow-crayola);
  box-shadow: var(--shadow-1);
  z-index: 1;
}

.icon-box::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--eerie-black-1);
  border-radius: inherit;
  z-index: -1;
}

.icon-box ion-icon { --ionicon-stroke-width: 35px; }

article { display: none; }

article.active {
  display: block;
  animation: fade 0.5s ease backwards;
}

@keyframes fade {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.h2,
.h3,
.h4,
.h5 {
  color: var(--white-2);
  text-transform: capitalize;
}

.h2 { font-size: var(--fs-1); }

.h3 { font-size: var(--fs-2); }

.h4 { font-size: var(--fs-4); }

.h5 {
  font-size: var(--fs-7);
  font-weight: var(--fw-500);
}

.article-title {
  position: relative;
  padding-bottom: 7px;
}

.article-title::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 30px;
  height: 3px;
  background: var(--text-gradient-yellow);
  border-radius: 3px;
}

.has-scrollbar::-webkit-scrollbar {
  width: 5px; /* for vertical scrollbar */
  height: 5px; /* for horizontal scrollbar */
}

.has-scrollbar::-webkit-scrollbar-track {
  background: var(--onyx);
  border-radius: 5px;
}

.has-scrollbar::-webkit-scrollbar-thumb {
  background: var(--orange-yellow-crayola);
  border-radius: 5px;
}

.has-scrollbar::-webkit-scrollbar-button { width: 20px; }

.content-card {
  position: relative;
  background: var(--border-gradient-onyx);
  padding: 15px;
  padding-top: 45px;
  border-radius: 14px;
  box-shadow: var(--shadow-2);
  cursor: pointer;
  z-index: 1;
}

.content-card::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--bg-gradient-jet);
  border-radius: inherit;
  z-index: -1;
}





/*-----------------------------------*\
  #MAIN
\*-----------------------------------*/

main {
  margin: 15px 12px;
  margin-bottom: 75px;
  min-width: 259px;
}





/*-----------------------------------*\
  #SIDEBAR
\*-----------------------------------*/

.sidebar {
  margin-bottom: 15px;
  max-height: 112px;
  overflow: hidden;
  transition: var(--transition-2);
}

.sidebar.active { max-height: 405px; }

.sidebar-info {
  position: relative;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 15px;
}

.avatar-box {
  background: var(--bg-gradient-onyx);
  border-radius: 20px;
}

.info-content .name {
  color: var(--white-2);
  font-size: var(--fs-3);
  font-weight: var(--fw-500);
  letter-spacing: -0.25px;
  margin-bottom: 10px;
}

.info-content .title {
  color: var(--white-1);
  background: var(--onyx);
  font-size: var(--fs-8);
  font-weight: var(--fw-300);
  width: max-content;
  padding: 3px 12px;
  border-radius: 8px;
}

.info_more-btn {
  position: absolute;
  top: -15px;
  right: -15px;
  border-radius: 0 15px;
  font-size: 13px;
  color: var(--orange-yellow-crayola);
  background: var(--border-gradient-onyx);
  padding: 10px;
  box-shadow: var(--shadow-2);
  transition: var(--transition-1);
  z-index: 1;
}

.info_more-btn::before {
  content: "";
  position: absolute;
  inset: 1px;
  border-radius: inherit;
  background: var(--bg-gradient-jet);
  transition: var(--transition-1);
  z-index: -1;
}

.info_more-btn:hover,
.info_more-btn:focus { background: var(--bg-gradient-yellow-1); }

.info_more-btn:hover::before,
.info_more-btn:focus::before { background: var(--bg-gradient-yellow-2); }

.info_more-btn span { display: none; }

.sidebar-info_more {
  opacity: 0;
  visibility: hidden;
  transition: var(--transition-2);
}

.sidebar.active .sidebar-info_more {
  opacity: 1;
  visibility: visible;
}

.contacts-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 16px;
}

.contact-item {
  min-width: 100%;
  display: flex;
  align-items: center;
  gap: 16px;
}

.contact-info {
  max-width: calc(100% - 46px);
  width: calc(100% - 46px);
}

.contact-title {
  color: var(--light-gray-70);
  font-size: var(--fs-8);
  text-transform: uppercase;
  margin-bottom: 2px;
}

.contact-info :is(.contact-link, time, address) {
  color: var(--white-2);
  font-size: var(--fs-7);
}

.contact-info address { font-style: normal; }

.social-list {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 15px;
  padding-bottom: 4px;
  padding-left: 7px;
}

.social-item .social-link {
  color: var(--light-gray-70);
  font-size: 18px;
}


.social-item .social-link:hover { color: var(--light-gray); }





/*-----------------------------------*\
  #NAVBAR
\*-----------------------------------*/

.navbar {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background: hsla(147, 85%, 43%, 0.75);
  backdrop-filter: blur(10px);
  border: 1px solid var(--jet);
  border-radius: 12px 12px 0 0;
  box-shadow: var(--shadow-2);
  z-index: 5;
}

.navbar-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  padding: 0 10px;
}

.navbar-link {
  color: var(--light-gray);
  font-size: var(--fs-8);
  padding: 20px 7px;
  transition: color var(--transition-1);
}

.navbar-link:hover,
.navbar-link:focus { color: var(--light-gray-70); }

.navbar-link.active { color: var(--orange-yellow-crayola); }





/*-----------------------------------*\
  #ABOUT
\*-----------------------------------*/

.about .article-title { margin-bottom: 15px; }

.about-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
}

.about-text p { margin-bottom: 15px; }



/**
 * #service 
 */

.service { margin-bottom: 35px; }

.service-title { margin-bottom: 20px; }

.service-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
}

.service-item {
  position: relative;
  background: var(--border-gradient-onyx);
  padding: 20px;
  border-radius: 14px;
  box-shadow: var(--shadow-2);
  z-index: 1;
}

.service-item::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--bg-gradient-jet);
  border-radius: inherit;
  z-index: -1;
}

.service-icon-box { margin-bottom: 10px; }

.service-icon-box img { margin: auto; }

.service-content-box { text-align: center; }

.service-item-title { margin-bottom: 7px; }

.service-item-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-3);
  line-height: 1.6;
}


/**
 * #testimonials 
 */

.testimonials { margin-bottom: 30px; }

.testimonials-title { margin-bottom: 20px; }

.testimonials-list {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 15px;
  margin: 0 -15px;
  padding: 25px 15px;
  padding-bottom: 35px;
  overflow-x: auto;
  scroll-behavior: smooth;
  overscroll-behavior-inline: contain;
  scroll-snap-type: inline mandatory;
}

.testimonials-item {
  min-width: 100%;
  scroll-snap-align: center;
}

.testimonials-avatar-box {
  position: absolute;
  top: 0;
  left: 0;
  transform: translate(15px, -25px);
  background: var(--bg-gradient-onyx);
  border-radius: 14px;
  box-shadow: var(--shadow-1);
}

.testimonials-item-title { margin-bottom: 7px; }

.testimonials-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
  display: -webkit-box;
  line-clamp: 4;
  -webkit-line-clamp: 4;
  -webkit-box-orient: vertical;
  overflow: hidden;
}


/**
 * #testimonials-modal
 */

.modal-container {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-y: auto;
  overscroll-behavior: contain;
  z-index: 20;
  pointer-events: none;
  visibility: hidden;
}

.modal-container::-webkit-scrollbar { display: none; }

.modal-container.active {
  pointer-events: all;
  visibility: visible;
}

.overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background: hsl(0, 0%, 5%);
  opacity: 0;
  visibility: hidden;
  pointer-events: none;
  z-index: 1;
  transition: var(--transition-1);
}

.overlay.active {
  opacity: 0.8;
  visibility: visible;
  pointer-events: all;
}

.testimonials-modal {
  background: var(--eerie-black-2);
  position: relative;
  padding: 15px;
  margin: 15px 12px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  box-shadow: var(--shadow-5);
  transform: scale(1.2);
  opacity: 0;
  transition: var(--transition-1);
  z-index: 2;
}

.modal-container.active .testimonials-modal {
  transform: scale(1);
  opacity: 1;
}

.modal-close-btn {
  position: absolute;
  top: 15px;
  right: 15px;
  background: var(--onyx);
  border-radius: 8px;
  width: 32px;
  height: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: var(--white-2);
  font-size: 18px;
  opacity: 0.7;
}

.modal-close-btn:hover,
.modal-close-btn:focus { opacity: 1; }

.modal-close-btn ion-icon { --ionicon-stroke-width: 50px; }

.modal-avatar-box {
  background: var(--bg-gradient-onyx);
  width: max-content;
  border-radius: 14px;
  margin-bottom: 15px;
  box-shadow: var(--shadow-2);
}

.modal-img-wrapper > img { display: none; }

.modal-title { margin-bottom: 4px; }

.modal-content time {
  font-size: var(--fs-6);
  color: var(--light-gray-70);
  font-weight: var(--fw-300);
  margin-bottom: 10px;
}

.modal-content p {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
}


/**
 * #clients 
 */

.clients { margin-bottom: 15px; }

.clients-list {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  gap: 15px;
  margin: 0 -15px;
  padding: 25px;
  padding-bottom: 25px;
  overflow-x: auto;
  scroll-behavior: smooth;
  overscroll-behavior-inline: contain;
  scroll-snap-type: inline mandatory;
  scroll-padding-inline: 25px;
}

.clients-item {
  min-width: 50%;
  scroll-snap-align: start;
}

.clients-item img {
  width: 100%;
  filter: grayscale(1);
  transition: var(--transition-1);
}

.clients-item img:hover { filter: grayscale(0); }





/*-----------------------------------*\
  #RESUME
\*-----------------------------------*/

.article-title { margin-bottom: 30px; }


/**
 * education and experience 
 */

.timeline { margin-bottom: 30px; }

.timeline .title-wrapper {
  display: flex;
  align-items: center;
  gap: 15px;
  margin-bottom: 25px;
}

.timeline-list {
  font-size: var(--fs-6);
  margin-left: 45px;
}

.timeline-item { position: relative; }

.timeline-item:not(:last-child) { margin-bottom: 20px; }

.timeline-item-title {
  font-size: var(--fs-6);
  line-height: 1.3;
  margin-bottom: 7px;
}

.timeline-list span {
  color: var(--vegas-gold);
  font-weight: var(--fw-400);
  line-height: 1.6;
}

.timeline-item:not(:last-child)::before {
  content: "";
  position: absolute;
  top: -25px;
  left: -30px;
  width: 1px;
  height: calc(100% + 50px);
  background: var(--jet);
}

.timeline-item::after {
  content: "";
  position: absolute;
  top: 5px;
  left: -33px;
  height: 6px;
  width: 6px;
  background: var(--text-gradient-yellow);
  border-radius: 50%;
  box-shadow: 0 0 0 4px var(--jet);
}

.timeline-text {
  color: var(--light-gray);
  font-weight: var(--fw-300);
  line-height: 1.6;
}


/**
 * skills 
 */

.skills-title { margin-bottom: 20px; }

.skills-list { padding: 20px; }


.skills-item:not(:last-child) { margin-bottom: 15px; }

.skill .title-wrapper {
  display: flex;
  align-items: center;
  gap: 5px;
  margin-bottom: 8px;
}

.skill .title-wrapper data {
  color: var(--light-gray);
  font-size: var(--fs-7);
  font-weight: var(--fw-300);
}

.skill-progress-bg {
  background: var(--jet);
  width: 100%;
  height: 8px;
  border-radius: 10px;
}

.skill-progress-fill {
  background: var(--text-gradient-yellow);
  height: 100%;
  border-radius: inherit;
}





/*-----------------------------------*\
  #PORTFOLIO
\*-----------------------------------*/

.filter-list { display: none; }

.filter-select-box {
  position: relative;
  margin-bottom: 25px;
}

.filter-select {
  background: var(--eerie-black-2);
  color: var(--light-gray);
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding: 12px 16px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
}

.filter-select.active .select-icon { transform: rotate(0.5turn); }

.select-list {
  background: var(--eerie-black-2);
  position: absolute;
  top: calc(100% + 6px);
  width: 100%;
  padding: 6px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  z-index: 2;
  opacity: 0;
  visibility: hidden;
  pointer-events: none;
  transition: 0.15s ease-in-out;
}

.filter-select.active + .select-list {
  opacity: 1;
  visibility: visible;
  pointer-events: all;
}

.select-item button {
  background: var(--eerie-black-2);
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  text-transform: capitalize;
  width: 100%;
  padding: 8px 10px;
  border-radius: 8px;
}

.select-item button:hover { --eerie-black-2: hsl(240, 58%, 48%); }

.project-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 30px;
  margin-bottom: 10px;
}

.project-item { display: none; }

.project-item.active {
  display: block;
  animation: scaleUp 0.25s ease forwards;
}

@keyframes scaleUp {
  0% { transform: scale(0.5); }
  100% { transform: scale(1); }
}

.project-item > a { width: 100%; }

.project-img {
  position: relative;
  width: 100%;
  height: 200px;
  border-radius: 16px;
  overflow: hidden;
  margin-bottom: 15px;
}

.project-img::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: transparent;
  z-index: 1;
  transition: var(--transition-1);
}

.project-item > a:hover .project-img::before { background: hsla(0, 0%, 0%, 0.5); }

.project-item-icon-box {
  --scale: 0.8;

  background: var(--jet);
  color: var(--orange-yellow-crayola);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) scale(var(--scale));
  font-size: 20px;
  padding: 18px;
  border-radius: 12px;
  opacity: 0;
  z-index: 1;
  transition: var(--transition-1);
}

.project-item > a:hover .project-item-icon-box {
  --scale: 1;
  opacity: 1;
}

.project-item-icon-box ion-icon { --ionicon-stroke-width: 50px; }

.project-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: var(--transition-1);
}

.project-item > a:hover img { transform: scale(1.1); }

.project-title,
.project-category { margin-left: 10px; }

.project-title {
  color: var(--white-2);
  font-size: var(--fs-5);
  font-weight: var(--fw-400);
  text-transform: capitalize;
  line-height: 1.3;
}

.project-category {
  color: var(--light-gray-70);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
}





/*-----------------------------------*\
  #BLOG
\*-----------------------------------*/

.blog-posts { margin-bottom: 10px; }

.blog-posts-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
}

.blog-post-item > a {
  position: relative;
  background: var(--border-gradient-onyx);
  height: 100%;
  box-shadow: var(--shadow-4);
  border-radius: 16px;
  z-index: 1;
}

.blog-post-item > a::before {
  content: "";
  position: absolute;
  inset: 1px;
  border-radius: inherit;
  background: var(--eerie-black-1);
  z-index: -1;
}

.blog-banner-box {
  width: 100%;
  height: 200px;
  border-radius: 12px;
  overflow: hidden;
}

.blog-banner-box img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: var(--transition-1);
}

.blog-post-item > a:hover .blog-banner-box img { transform: scale(1.1); }

.blog-content { padding: 15px; }

.blog-meta {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 7px;
  margin-bottom: 10px;
}

.blog-meta :is(.blog-category, time) {
  color: var(--light-gray-70);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
}

.blog-meta .dot {
  background: var(--light-gray-70);
  width: 4px;
  height: 4px;
  border-radius: 4px;
}

.blog-item-title {
  margin-bottom: 10px;
  line-height: 1.3;
  transition: var(--transition-1);
}

.blog-post-item > a:hover .blog-item-title { color: var(--orange-yellow-crayola); }

.blog-text {
  color: var(--light-gray);
  font-size: var(--fs-6);
  font-weight: var(--fw-300);
  line-height: 1.6;
}





/*-----------------------------------*\
  #CONTACT
\*-----------------------------------*/


.contact-form { margin-bottom: 10px; }

.form-title { margin-bottom: 20px; }

.input-wrapper {
  display: grid;
  grid-template-columns: 1fr;
  gap: 25px;
  margin-bottom: 25px;
}

.form-input {
  color: var(--white-2);
  font-size: var(--fs-6);
  font-weight: var(--fw-400);
  padding: 13px 20px;
  border: 1px solid var(--jet);
  border-radius: 14px;
  outline: none;
}

.form-input::placeholder { font-weight: var(--fw-500); }

.form-input:focus { border-color: var(--orange-yellow-crayola); }

textarea.form-input {
  min-height: 100px;
  height: 120px;
  max-height: 200px;
  resize: vertical;
  margin-bottom: 25px;
}

textarea.form-input::-webkit-resizer { display: none; }

.form-input:focus:invalid { border-color: var(--bittersweet-shimmer); }

.form-btn {
  position: relative;
  width: 100%;
  background: var(--border-gradient-onyx);
  color: var(--orange-yellow-crayola);
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 13px 20px;
  border-radius: 14px;
  font-size: var(--fs-6);
  text-transform: capitalize;
  box-shadow: var(--shadow-3);
  z-index: 1;
  transition: var(--transition-1);
}

.form-btn::before {
  content: "";
  position: absolute;
  inset: 1px;
  background: var(--bg-gradient-jet);
  border-radius: inherit;
  z-index: -1;
  transition: var(--transition-1);
}

.form-btn ion-icon { font-size: 16px; }

.form-btn:hover { background: var(--bg-gradient-yellow-1); }

.form-btn:hover::before { background: var(--bg-gradient-yellow-2); }

.form-btn:disabled {
  opacity: 0.7;
  cursor: not-allowed;
}

.form-btn:disabled:hover { background: var(--border-gradient-onyx); }

.form-btn:disabled:hover::before { background: var(--bg-gradient-jet); }





/*-----------------------------------*\
  #RESPONSIVE
\*-----------------------------------*/

/**
 * responsive larger than 450px screen
 */

@media (min-width: 450px) {

  /**
   * client
   */

  .clients-item { min-width: calc(33.33% - 10px); }



  /**
   * #PORTFOLIO, BLOG 
   */

  .project-img,
  .blog-banner-box { height: auto; }

}





/**
 * responsive larger than 580px screen
 */

@media (min-width: 580px) {

  /**
   * CUSTOM PROPERTY
   */

  :root {

    /**
     * typography
     */

    --fs-1: 32px;
    --fs-2: 24px;
    --fs-3: 26px;
    --fs-4: 18px;
    --fs-6: 15px;
    --fs-7: 15px;
    --fs-8: 12px;

  }



  /**
   * #REUSED STYLE
   */

  .sidebar, article {
    width: 520px;
    margin-inline: auto;
    padding: 30px;
  }

  .article-title {
    font-weight: var(--fw-600);
    padding-bottom: 15px;
  }

  .article-title::after {
    width: 40px;
    height: 5px;
  }

  .icon-box {
    width: 48px;
    height: 48px;
    border-radius: 12px;
    font-size: 18px;
  }



  /**
   * #MAIN
   */

  main {
    margin-top: 60px;
    margin-bottom: 100px;
  }



  /**
   * #SIDEBAR
   */

  .sidebar {
    max-height: 180px;
    margin-bottom: 30px;
  }

  .sidebar.active { max-height: 584px; }

  .sidebar-info { gap: 25px; }

  .avatar-box { border-radius: 30px; }

  .avatar-box img { width: 120px; }

  .info-content .name { margin-bottom: 15px; }

  .info-content .title { padding: 5px 18px; }

  .info_more-btn {
    top: -30px;
    right: -30px;
    padding: 10px 15px;
  }

  .info_more-btn span {
    display: block;
    font-size: var(--fs-8);
  }

  .info_more-btn ion-icon { display: none; }

  .separator { margin: 32px 0; }

  .contacts-list { gap: 20px; }

  .contact-info {
    max-width: calc(100% - 64px);
    width: calc(100% - 64px);
  }



  /**
   * #NAVBAR
   */

  .navbar { border-radius: 20px 20px 0 0; }

  .navbar-list { gap: 20px; }

  .navbar-link { --fs-8: 14px; }



  /**
   * #ABOUT
   */

  .about .article-title { margin-bottom: 20px; }

  .about-text { margin-bottom: 40px; }

  /* service */

  .service-item {
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    gap: 18px;
    padding: 30px;
  }

  .service-icon-box {
    margin-bottom: 0;
    margin-top: 5px;
  }

  .service-content-box { text-align: left; }

  /* testimonials */

  .testimonials-title { margin-bottom: 25px; }

  .testimonials-list {
    gap: 30px;
    margin: 0 -30px;
    padding: 30px;
    padding-bottom: 35px;
  }

  .content-card {
    padding: 30px;
    padding-top: 25px;
  }

  .testimonials-avatar-box {
    transform: translate(30px, -30px);
    border-radius: 20px;
  }

  .testimonials-avatar-box img { width: 80px; }

  .testimonials-item-title {
    margin-bottom: 10px;
    margin-left: 95px;
  }

  .testimonials-text {
    line-clamp: 2;
    -webkit-line-clamp: 2;
  }

  /* testimonials modal */

  .modal-container { padding: 20px; }

  .testimonials-modal {
    display: flex;
    justify-content: flex-start;
    align-items: stretch;
    gap: 25px;
    padding: 30px;
    border-radius: 20px;
  }

  .modal-img-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .modal-avatar-box {
    border-radius: 18px;
    margin-bottom: 0;
  }

  .modal-avatar-box img { width: 65px; }

  .modal-img-wrapper > img {
    display: block;
    flex-grow: 1;
    width: 35px;
  }

  /* clients */

  .clients-list {
    gap: 50px;
    margin: 0 -30px;
    padding: 45px;
    scroll-padding-inline: 45px;
  }

  .clients-item { min-width: calc(33.33% - 35px); }



  /**
   * #RESUME
   */

  .timeline-list { margin-left: 65px; }

  .timeline-item:not(:last-child)::before { left: -40px; }

  .timeline-item::after {
    height: 8px;
    width: 8px;
    left: -43px;
  }

  .skills-item:not(:last-child) { margin-bottom: 25px; }



  /**
   * #PORTFOLIO, BLOG
   */

  .project-img, .blog-banner-box { border-radius: 16px; }

  .blog-posts-list { gap: 30px; }

  .blog-content { padding: 25px; }



  /**
   * #CONTACT
   */

  .mapbox {
    height: 380px;
    border-radius: 18px;
  }

  .input-wrapper {
    gap: 30px;
    margin-bottom: 30px;
  }

  .form-input { padding: 15px 20px; }

  textarea.form-input { margin-bottom: 30px; }

  .form-btn {
    --fs-6: 16px;
    padding: 16px 20px;
  }

  .form-btn ion-icon { font-size: 18px; }

}





/**
 * responsive larger than 768px screen
 */

@media (min-width: 768px) {

  /**
   * REUSED STYLE
   */

  .sidebar, article { width: 700px; }

  .has-scrollbar::-webkit-scrollbar-button { width: 100px; }



  /**
   * SIDEBAR
   */

  .contacts-list {
    grid-template-columns: 1fr 1fr;
    gap: 30px 15px;
  }



  /**
   * NAVBAR
   */

  .navbar-link { --fs-8: 15px; }



  /**
   * ABOUT
   */

  /* testimonials modal */

  .testimonials-modal {
    gap: 35px;
    max-width: 680px;
  }

  .modal-avatar-box img { width: 80px; }



  /**
   * PORTFOLIO
   */

  .article-title { padding-bottom: 20px; }

  .filter-select-box { display: none; }

  .filter-list {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 25px;
    padding-left: 5px;
    margin-bottom: 30px;
  }

  .filter-item button {
    color: var(--light-gray);
    font-size: var(--fs-5);
    transition: var(--transition-1);
  }

  .filter-item button:hover { color: var(--light-gray-70); }

  .filter-item button.active { color: var(--orange-yellow-crayola); }

  /* portfolio and blog grid */

  .project-list, .blog-posts-list { grid-template-columns: 1fr 1fr; }



  /**
   * CONTACT
   */

  .input-wrapper { grid-template-columns: 1fr 1fr; }

  .form-btn {
    width: max-content;
    margin-left: auto;
  }
  
}





/**
 * responsive larger than 1024px screen
 */

@media (min-width: 1024px) {

  /**
   * CUSTOM PROPERTY
   */

  :root {

    /**
    * shadow
    */

    --shadow-1: -4px 8px 24px hsla(0, 0%, 0%, 0.125);
    --shadow-2: 0 16px 30px hsla(0, 0%, 0%, 0.125);
    --shadow-3: 0 16px 40px hsla(0, 0%, 0%, 0.125);

  }



  /**
   * REUSED STYLE
   */

  .sidebar, article {
    width: 950px;
    box-shadow: var(--shadow-5);
  }



  /**
   * MAIN 
   */

  main { margin-bottom: 60px; }

  .main-content {
    position: relative;
    width: max-content;
    margin: auto;
  }



  /**
   * NAVBAR
   */

  .navbar {
    position: absolute;
    bottom: auto;
    top: 0;
    left: auto;
    right: 0;
    width: max-content;
    border-radius: 0 20px;
    padding: 0 20px;
    box-shadow: none;
  }

  .navbar-list {
    gap: 30px;
    padding: 0 20px;
  }

  .navbar-link { font-weight: var(--fw-500); }



  /**
   * ABOUT
   */

  /* service */

  .service-list {
    grid-template-columns: 1fr 1fr;
    gap: 20px 25px;
  }

  /* testimonials */

  .testimonials-item { min-width: calc(50% - 15px); }

  /* clients */

  .clients-item { min-width: calc(25% - 38px); }



  /**
   * PORTFOLIO
   */

  .project-list { grid-template-columns: repeat(3, 1fr); }



  /**
   * BLOG
   */

  .blog-banner-box { height: 230px; }

}





/**
 * responsive larger than 1250px screen
 */

@media (min-width: 1250px) {

  /**
   * RESET
   */

  body::-webkit-scrollbar { width: 20px; }

  body::-webkit-scrollbar-track { background: var(--smoky-black); }

  body::-webkit-scrollbar-thumb {
    border: 5px solid var(--smoky-black);
    background: hsla(0, 0%, 100%, 0.1);
    border-radius: 20px;
    box-shadow: inset 1px 1px 0 hsla(0, 0%, 100%, 0.11),
                inset -1px -1px 0 hsla(0, 0%, 100%, 0.11);
  }

  body::-webkit-scrollbar-thumb:hover { background: hsla(0, 0%, 100%, 0.15); }

  body::-webkit-scrollbar-button { height: 60px; }



  /**
   * REUSED STYLE
   */

  .sidebar, article { width: auto; }

  article { min-height: 100%; }



  /**
   * MAIN
   */

  main {
    max-width: 1200px;
    margin-inline: auto;
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 25px;
  }

  .main-content {
    min-width: 75%;
    width: 75%;
    margin: 0;
  }



  /**
   * SIDEBAR
   */

  .sidebar {
    position: sticky;
    top: 60px;
    max-height: max-content;
    height: 100%;
    margin-bottom: 0;
    padding-top: 60px;
    z-index: 1;
  }

  .sidebar-info { flex-direction: column; }

  .avatar-box img { width: 150px; }

  .info-content .name {
    white-space: nowrap;
    text-align: center;
  }

  .info-content .title { margin: auto; }

  .info_more-btn { display: none; }

  .sidebar-info_more {
    opacity: 1;
    visibility: visible;
  }

  .contacts-list { grid-template-columns: 1fr; }

  .contact-info :is(.contact-link) {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .contact-info :is(.contact-link, time, address) {
    --fs-7: 14px;
    font-weight: var(--fw-300);
  }

  .separator:last-of-type {
    margin: 15px 0;
    opacity: 0;
  }

  .social-list { justify-content: center; }



  /**
	 * RESUME
	 */

  .timeline-text { max-width: 700px; }

}



#Style.js code

'use strict';


    document.getElementById("motivateButton").addEventListener("click", function() {
        const quotes = [
            "Believe in yourself and all that you are!",
            "Success is not final, failure is not fatal: It is the courage to continue that counts.",
            "Your future is created by what you do today, not tomorrow.",
            "Dream big, work hard, stay focused, and surround yourself with good people."
        ];
        
        const randomQuote = quotes[Math.floor(Math.random() * quotes.length)];
        document.getElementById("motivationText").innerText = randomQuote;
    });


// element toggle function
const elementToggleFunc = function (elem) { elem.classList.toggle("active"); }



// sidebar variables
const sidebar = document.querySelector("[data-sidebar]");
const sidebarBtn = document.querySelector("[data-sidebar-btn]");

// sidebar toggle functionality for mobile
sidebarBtn.addEventListener("click", function () { elementToggleFunc(sidebar); });



// testimonials variables
const testimonialsItem = document.querySelectorAll("[data-testimonials-item]");
const modalContainer = document.querySelector("[data-modal-container]");
const modalCloseBtn = document.querySelector("[data-modal-close-btn]");
const overlay = document.querySelector("[data-overlay]");

// modal variable
const modalImg = document.querySelector("[data-modal-img]");
const modalTitle = document.querySelector("[data-modal-title]");
const modalText = document.querySelector("[data-modal-text]");

// modal toggle function
const testimonialsModalFunc = function () {
  modalContainer.classList.toggle("active");
  overlay.classList.toggle("active");
}

// add click event to all modal items
for (let i = 0; i < testimonialsItem.length; i++) {

  testimonialsItem[i].addEventListener("click", function () {

    modalImg.src = this.querySelector("[data-testimonials-avatar]").src;
    modalImg.alt = this.querySelector("[data-testimonials-avatar]").alt;
    modalTitle.innerHTML = this.querySelector("[data-testimonials-title]").innerHTML;
    modalText.innerHTML = this.querySelector("[data-testimonials-text]").innerHTML;

    testimonialsModalFunc();

  });

}

// add click event to modal close button
modalCloseBtn.addEventListener("click", testimonialsModalFunc);
overlay.addEventListener("click", testimonialsModalFunc);



// custom select variables
const select = document.querySelector("[data-select]");
const selectItems = document.querySelectorAll("[data-select-item]");
const selectValue = document.querySelector("[data-selecct-value]");
const filterBtn = document.querySelectorAll("[data-filter-btn]");

select.addEventListener("click", function () { elementToggleFunc(this); });

// add event in all select items
for (let i = 0; i < selectItems.length; i++) {
  selectItems[i].addEventListener("click", function () {

    let selectedValue = this.innerText.toLowerCase();
    selectValue.innerText = this.innerText;
    elementToggleFunc(select);
    filterFunc(selectedValue);

  });
}

// filter variables
const filterItems = document.querySelectorAll("[data-filter-item]");

const filterFunc = function (selectedValue) {

  for (let i = 0; i < filterItems.length; i++) {

    if (selectedValue === "all") {
      filterItems[i].classList.add("active");
    } else if (selectedValue === filterItems[i].dataset.category) {
      filterItems[i].classList.add("active");
    } else {
      filterItems[i].classList.remove("active");
    }

  }

}

// add event in all filter button items for large screen
let lastClickedBtn = filterBtn[0];

for (let i = 0; i < filterBtn.length; i++) {

  filterBtn[i].addEventListener("click", function () {

    let selectedValue = this.innerText.toLowerCase();
    selectValue.innerText = this.innerText;
    filterFunc(selectedValue);

    lastClickedBtn.classList.remove("active");
    this.classList.add("active");
    lastClickedBtn = this;

  });

}



// contact form variables
const form = document.querySelector("[data-form]");
const formInputs = document.querySelectorAll("[data-form-input]");
const formBtn = document.querySelector("[data-form-btn]");

// add event to all form input field
for (let i = 0; i < formInputs.length; i++) {
  formInputs[i].addEventListener("input", function () {

    // check form validation
    if (form.checkValidity()) {
      formBtn.removeAttribute("disabled");
    } else {
      formBtn.setAttribute("disabled", "");
    }

  });
}



// page navigation variables
const navigationLinks = document.querySelectorAll("[data-nav-link]");
const pages = document.querySelectorAll("[data-page]");

// add event to all nav link
for (let i = 0; i < navigationLinks.length; i++) {
  navigationLinks[i].addEventListener("click", function () {

    for (let i = 0; i < pages.length; i++) {
      if (this.innerHTML.toLowerCase() === pages[i].dataset.page) {
        pages[i].classList.add("active");
        navigationLinks[i].classList.add("active");
        window.scrollTo(0, 0);
      } else {
        pages[i].classList.remove("active");
        navigationLinks[i].classList.remove("active");
      }
    }

  });
}



