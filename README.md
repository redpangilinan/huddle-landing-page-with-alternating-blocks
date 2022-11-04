# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/solution-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML
- CSS
- JavaScript
- [Bootstrap](https://getbootstrap.com/) - CSS Framework
- [AOS](https://michalsnik.github.io/aos/) - Animate on Scroll Library

### What I learned

Here is the codes that I wanna highlight. I learned a lot from these sections.


#### Html Highlight

This long html section is the footer of the webpage, it took me a few hours to code and gave me a lot of frustration but puzzling the design until it is finished with full responsiveness is very satisfying.

```html
<footer class="position-relative">
    <section class="community-box">
      <div class="container">
        <div class="card shadow-main position-absolute responsive-top start-50 translate-middle zoom">
          <div class="card-body text-center">
            <div class="row d-flex justify-content-center align-items-center">
              <h2 class="heading">Ready To Build Your Community?</h2>
              <a href="#" class="btn-getstarted shadow-main highlight">Get Started For Free</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="footer-content">
      <div class="container footer-link">
        <div class="row">
          <div class="col px-4 responsive-footer" data-aos="fade-up">
            <img src="./images/logo.svg" alt="" class="footer-huddle zoom mb-5">
          </div>
        </div>
        <div class="row">
          <div class="col-md-4 responsive-footer d-flex justify-content-center align-content-center justify-content-md-start align-content-md-start" data-aos="fade-up">
            <address>
              <ul class="nav flex-column address-font fa-ul">
                <li class="nav-item mb-4">
                  <a href="http://maps.google.com/?q=1 23 Buchman Drive, Albany,ny, 12211  United States" target="_blank"><span class="fa-li"><i class="fa-solid fa-location-dot"></i></i></span>23 Buchman Drive, Albany,ny,<br> 12211 United States</a>
                </li>
                <li class="nav-item mb-4">
                  <a href="tel:+1-543-123-4567"><span class="fa-li"><i class="fa-solid fa-phone-volume"></i></span>+1-543-123-4567</a>
                </li>
                <li class="nav-item mb-4">
                  <a href="mailto:example@huddle.com"><span class="fa-li"><i class="fa-solid fa-envelope"></i></span>example@huddle.com</a>
                </li>
              </ul>
            </address>
          </div>
          <div class="col-2 ms-lg-3 responsive-footer" data-aos="fade-up">
            <ul class="nav flex-column">
              <li class="nav-item mb-1">
                <a href="#" class="nav-link">About Us</a>
              </li>
              <li class="nav-item mb-1">
                <a href="#" class="nav-link">What We Do</a>
              </li>
              <li class="nav-item mb-1">
                <a href="#" class="nav-link">FAQ</a>
              </li>
            </ul>
          </div>
          <div class="col-2 ms-lg-3 responsive-footer" data-aos="fade-up">
            <ul class="nav flex-column">
              <li class="nav-item mb-1">
                <a href="#" class="nav-link">Career</a>
              </li>
              <li class="nav-item mb-1">
                <a href="#" class="nav-link">Blog</a>
              </li>
              <li class="nav-item mb-1">
                <a href="#" class="nav-link">Contact Us</a>
              </li>
            </ul>
          </div>
          <div class="col-md mb-md-5 mt-5 mt-md-0 d-flex justify-content-center align-content-md-center" data-aos="fade-left">
            <ul class="list-unstyled d-flex">
              <li class="ms-0">
                <a href="#" class="nav-link zoom-2"><i class="fa-brands fa-square-facebook socials"></i></a>
              </li>
              <li class="ms-0">
                <a href="#" class="nav-link zoom-2"><i class="fa-brands fa-square-twitter socials"></i></a>
              </li>
              <li class="ms-0">
                <a href="#" class="nav-link zoom-2"><i class="fa-brands fa-square-instagram socials"></i></a>
              </li>
            </ul>
          </div>
        </div>
        <div class="row">
          <div class="col d-flex footer-end responsive-footer">
            <p class="attribution">
              Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
              Coded by <a href="https://redpangilinan.github.io/portfolio/" target="_blank">Red Pangilinan</a>.
            </p>
            <p class="ms-auto">&copy; Copyright 2018 Huddle. All rights reserved.</p>
          </div>
        </div>
      </div>
    </section>
  </footer>
```

#### CSS Highlight

I can't say I'm very proud of this CSS but this is the first time I used @media so it's a new experience for me. Probably not the best code out there but I learned a lot from coding this section and it gives a lot of satisfaction seeing your finished design with full responsiveness.
```css
@media only screen and (min-width: 993px) {
  .mobile {
    display: none;
  }

  body {
    background: url("images/bg-hero-desktop.svg") no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }

  .btn-tryfree {
    padding: 12px 60px 12px 60px;
    margin-right: 17px;

  }

  .huddle {
    max-height: 100%;
    max-width: 200px;
  }

  .responsive-gap {
    margin-top: 2rem;
  }

  footer {
    padding: 11rem 4rem 3.8rem 7.4rem;
  }

  .footer-end {
    margin-top: 2rem;
    margin-bottom: -1rem;
  }

  /* Card */
  .features {
    max-width: 77rem;
    min-height: 27.5rem;
    margin: 2rem;
  }

  .card-sub {
    color: hsl(208, 11%, 55%);
  }

  .card-subsize {
    padding: 0px 80px 0px 80px;
  }

  .responsive-top {
    top: -10% !important;
  }

  /* Community Box */
  .community-box .card {
    width: 100%;
    max-width: 50rem;
    padding: 2rem;
    height: 17.6rem;
  }

  .community-box .btn-getstarted {
    max-width: 25rem;
    padding: 1.8rem 0rem 1.8rem;
    border-radius: 3rem;
    margin-bottom: 3rem;
  }

  .community-box h2 {
    margin-bottom: 3rem;
  }
}

/* Responsive for Mobile*/
@media only screen and (max-width: 992px) {
  .desktop {
    display: none;
  }

  body {
    background: url("images/bg-hero-mobile.svg") no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }

  .btn-tryfree {
    padding: 4px 30px 4px 30px;
  }

  .btn-getstarted {
    padding: 16px 0px 16px 0px;
    max-width: 100%;
    display: flex;
    justify-content: center;
  }

  .huddle {
    max-height: 100%;
    max-width: 130px;
  }

  .responsive-gap {
    margin-top: 1.3rem;
  }

  .responsive-top {
    top: -10% !important;
  }

  @media only screen and (max-width: 767px) {
    .responsive-footer {
      width: 100%;
      text-align: center;
    }
    .responsive-top {
      top: -5% !important;
    }
  }

  footer {
    padding: 10rem 1rem 1rem 1rem;
  }

  /* Card */
  .features {
    margin: 0.7rem;
    margin: 2.5rem 0rem 2.5rem;
    text-align: center;
  }

  .card-body {
    margin: 0.5rem;
    text-align: center;
  }

  .card p {
    font-size: 16px;
    margin: 1rem 0rem 1rem;
  }

  .card img {
    margin: 2rem 0rem 3rem;
  }

  /* Community Box */
  .community-box .card {
    width: 100%;
    max-width: 43.5rem;
    padding: 1rem;
    height: 17rem;
  }

  .community-box .btn-getstarted {
    max-width: 20rem;
    padding: 1.4rem 0rem 1.4rem;
    border-radius: 3rem !important;
  }

  .community-box h2 {
    margin-bottom: 3rem;
  }
  
  @media only screen and (max-width: 739px) {
    .community-box .card {
      width: 100%;
      max-width: 95%;
      height: 16rem;
    }

    .community-box h2 {
      margin-bottom: 2rem;
    }

    .community-box .btn-getstarted {
      max-width: 18rem;
      padding: 1.4rem 0rem 1.4rem;
      border-radius: 3rem !important;
    }

    @media only screen and (max-width: 547px) {
      .community-box .card {
        width: 100%;
        max-width: 95%;
        height: 15.5rem;
      }

      .community-box .btn-getstarted {
        max-width: 16rem;
        padding: 1rem 0rem 1rem;
        border-radius: 3rem !important;
      }
    }
  }
}
```

### Continued development

I learned a lot about responsiveness in this project, that's why I will implement it in all of my future projects. I have learned a lot about techniques on setting up responsive webpages both in CSS and Bootstrap. Bootstrap makes responsive website development quicker although I find it frustrating at times. Still really good to use though, I also plan on using Bootstrap in most of my future projects because it makes me code quicker, which is the entire purpose of Bootstrap.

### Useful resources

- [Official Bootstrap Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/) - This is my reference for bootstrap.
- [Animate on Scroll Library](https://michalsnik.github.io/aos/) - Really good animation library that is quick and easy to setup.

## Author

- Website - [Red Pangilinan](https://redpangilinan.github.io/portfolio/)
- Frontend Mentor - [@redpangilinan](https://www.frontendmentor.io/profile/redpangilinan)
- Twitter - [@repulzor](https://twitter.com/repulzor)
- Facebook - [Red Pangilinan](https://www.facebook.com/redpangilinan715/)
- GitHub - [redpangilinan](https://github.com/redpangilinan)