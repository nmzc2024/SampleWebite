# SampleWebite

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Nicole Corla Portfolio</title>
    <link rel="stylesheet" href="assets/swiper-bundle.min.css" />
    <link rel="stylesheet" href="assets/newcss.css" />
    <link
      rel="stylesheet"
      href="https://unicons.iconscout.com/release/v4.0.8/css/line.css"
    />
  </head>

  <body oncontextmenu="return false">
    <header class="header" id="header">
      <nav class="nav container">
        <a href="#" class="nav__logo">Nicole Corla</a>
        <div class="nav__menu" id="nav-menu">
          <ul class="nav__list grid">
            <li class="nav__item">
              <a href="#home" class="nav__link active-link">
                <i class="uil uil-estate nav__icon"></i>Home
              </a>
            </li>
            <li class="nav__item">
              <a href="#about" class="nav__link">
                <i class="uil uil-user nav__icon"></i>About
              </a>
            </li>
            <li class="nav__item">
              <a href="#skills" class="nav__link">
                <i class="uil uil-file-alt nav__icon"></i>Skills
              </a>
            </li>
            <li class="nav__item">
              <a href="#portfolio" class="nav__link">
                <i class="uil uil-scenery nav__icon"></i>Projects
              </a>
            </li>
            <li class="nav__item">
              <a href="#contact" class="nav__link">
                <i class="uil uil-message nav__icon"></i>Contact
              </a>
            </li>
          </ul>
          <i class="uil uil-times nav__close" id="nav-close"></i>
        </div>
      </nav>
    </header>

    <!-- Home Section -->
    <main class="main">
      <section class="home section" id="home">
        <div class="home__container container grid">
          <div class="home__content grid">
            <div class="home__data">
              <h1 class="home__title">Hi, I'm Nicole Corla</h1>
              <h3 class="home__subtitle">
                Computer Science Master's Engineering Student
              </h3>
              <p class="home__description">
                GPA: 3.5 | Graduation Date: March 2026
              </p>
              <a href="#contact" class="button button--flex">
                Contact Me<i class="uil uil-message button__icon"></i>
              </a>
            </div>
          </div>

          <!-- Social Links -->
          <div class="home__social">
            <a
              href="https://www.linkedin.com/in/nicolezcorla/details/experience/"
              target="_blank"
              class="home__social-icon"
            >
              <i class="uil uil-linkedin-alt"></i> LinkedIn
            </a>
          </div>
        </div>
      </section>
    </main>

    <!-- Contact Section -->
    <section class="contact section" id="contact">
      <h2 class="section__title">Contact Me</h2>
      <span class="section__subtitle">Get in touch</span>
      <form action="" class="contact__form grid">
        <div class="contact__inputs grid">
          <div class="contact__content">
            <label for="name" class="content__label">Name</label>
            <input type="text" id="name" class="contact__input" />
          </div>
          <div class="contact__content">
            <label for="email" class="content__label">Email</label>
            <input type="email" id="email" class="contact__input" />
          </div>
        </div>
        <div class="contact__content">
          <label for="message" class="content__label">Message</label>
          <textarea
            id="message"
            cols="0"
            rows="7"
            class="contact__input"
          ></textarea>
        </div>
        <button type="submit" class="button button--flex">
          Send Message<i class="uil uil-message button__icon"></i>
        </button>
      </form>
    </section>

    <footer class="footer">
      <p class="footer__copy">&#169; Nicole Corla. All rights reserved.</p>
    </footer>
  </body>
</html>
