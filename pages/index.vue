<template>
  <div class="parent">
    <NavBarSite />
    <main class="parent__main container">
      <div class="parent__header">
        <div class="header__left">
          <h1 class="header__title">
            Learn<br>Any Foreign Language
          </h1>
          <p class="header__subtitle subtitle">
            With our teachers who write a program for
            each student, you will be able to make your
            first sketch after the first lesson.
          </p>
          <button type="button" class="btn btn-dark left__btn">Get started</button>
        </div>
        <div class="header__right">
          <img src="../assets/img/header-right-img.png" alt="Photo" class="header__img">
        </div>
      </div>
      <div class="parent__skills">
        <h2 class="title-h1 text-center">Skills</h2>
        <div class="skills__grid">
          <div class="grid__speaking">
            <div class="grid__container">
              <img src="../assets/img/speaking-img.png" alt="Photo" class="speaking__img">
              <div class="grid__block-text">
                <h3 class="block-text__title title-h2">Speaking</h3>
                <p class="block-text__subtitle">Improve your English skills and confidence.
                  Live classes and interactive lessons online.
                  20% extra free for a limited time only
                  <br>
                  <br>
                  Learn English online and improve your
                  skills through our high-quality courses
                  and resources – all designed for adult language learners.
                </p>
                <button class="btn btn-dark block-text__btn">Learn more</button>
              </div>
            </div>
          </div>
          <div class="grid__block-right">
            <div class="block-right__top">
              <div class="block-right__writing">
                <div class="grid__container">
                  <img src="../assets/img/writing.png" alt="Photo" class="speaking__img">
                  <div class="grid__block-text">
                    <h3 class="block-text__title title-h2">Writing</h3>
                    <p class="block-text__subtitle">One of the most important and extensive
                      areas of natural science, the science that
                      studies substances, also their composition
                    </p>
                    <button class="btn btn-dark block-text__btn">Learn more</button>
                  </div>
                </div>
              </div>
              <div class="block-right__reading">
                <div class="grid__container">
                  <img src="../assets/img/reading.png" alt="Photo" class="speaking__img">
                  <div class="grid__block-text">
                    <h3 class="block-text__title title-h2">Reading</h3>
                    <p class="block-text__subtitle">perception and response actions of the user
                      resulting from the use and/or upcoming use
                      of the product, system or service
                    </p>
                    <button class="btn btn-dark block-text__btn">Learn more</button>
                  </div>
                </div>
              </div>
            </div>
            <div class="block-right__bottom">
              <div class="bottom__listening">
                <div class="grid__container">

                  <div class="grid__block-text">
                    <div>
                      <h3 class="block-text__title title-h2">Listening</h3>
                      <p class="block-text__subtitle">Here you can find activities to practise
                        your listening skills. Listening will help you
                        to improve your understanding
                      </p>
                      <button class="btn btn-dark block-text__btn">Learn more</button>
                    </div>
                    <div>
                      <img src="../assets/img/listening.img.png" alt="Photo" class="speaking__img">
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="parent__about-us">
        <div class="about-us__block-left">
          <h1 class="about-us__title title-h1">
            About Us
          </h1>
          <p class="about-us__subtitle subtitle">
            The model offers a framework for discussing problems related to the user's experience, as well as possible
            ways and means of solving them. Application development begins at the top level (strategy), where the future
            software product is described quite abstractly from the point of view of the expectations of both users and
            the customer.
          </p>
          <div class="about-us__block-flex text-center">
            <div class="block-flex-one">
              <h4 class="title-h1">800</h4>
              <p class="subtitle">
                Pupils
              </p>
            </div>
            <div class="block-flex-two">
              <h4 class="title-h1">18</h4>
              <p class="subtitle">
                Teachers
              </p>
            </div>
            <div class="block-flex-three">
              <h4 class="title-h1">6</h4>
              <p class="subtitle">
                Foreign languages
              </p>
            </div>
          </div>
        </div>
        <div class="about-us__block-right">
          <img src="../assets/img/about-us-img.png" alt="Photo" class="block-right__img">
        </div>

      </div>
      <div class="parent__pricing">
        <h2 class="pricing__title title-h1 text-center">Pricing</h2>
        <div class="pricing__block-flex">
          <div class="block-flex-one">
            <img src="../assets/img/online-course.png" alt="Photo" class="block-flex-img">
            <h3 class="block-flex__title title-h2">Self-study online course</h3>
            <p class="block-flex__subtitle subtitle">
              Start learning English online in live classes
              with qualified EC teachers and students
              from all over the world.
            </p>
            <div class="block-flex__price text-center">
              <p class="price-text"><span class="price">£5.99</span> per month</p>
            </div>
          </div>
          <div class="block-flex-one">
            <img src="../assets/img/live-classes.png" alt="Photo" class="block-flex-img">
            <h3 class="block-flex__title title-h2">Live online classes</h3>
            <p class="block-flex__subtitle subtitle">
              Interactive group classes with expert
              teachers. Free 7-day trial
            </p>
            <div class="block-flex__price text-center mar-top">
              <p class="price-text"><span class="price">£12.99</span> per month</p>
            </div>
          </div>
          <div class="block-flex-one">
            <img src="../assets/img/personal-tutorial.png" alt="Photo" class="block-flex-img">
            <h3 class="block-flex__title title-h2">Personal Tuition</h3>
            <p class="block-flex__subtitle subtitle">
              Online one-to-one English tutoring – enjoy
              our first session for only $1
            </p>
            <div class="block-flex__price text-center">
              <p class="price-text"><span class="price">£20.99</span> per month</p>
            </div>
          </div>
        </div>
      </div>
      <div class="parent__contact-us">
        <div class="contact-us__container-flex">
          <div class="container-flex__left">
            <img src="../assets/img/contact-us-img.png" alt="Photo" class="left__img">
          </div>
          <div class="container-flex__right">
            <h2 class="right__title title-h2">Contact Us</h2>
            <p class="right__subtitle">
              Discover your current English level by taking our free
              online English test.Sign up to our newsletter for learning
              tips and free resource
            </p>
            <div class="right__block-input">
              <input type="text" class="block-input__input" placeholder="Enter Your E-mail">
              <button class="block-input__btn btn-dark">Subscribe</button>
            </div>
          </div>
        </div>
      </div>
    </main>
    <footer class="parent__footer">
      <div class="container">
        <div class="footer-flex">
          <div class="footer__block-left">
            <a class="navbar-brand" href="#">
              <img src="../assets/img/Logo.svg" alt="Logo" width="106" height="54">
            </a>
          </div>
          <div class="footer__block-right">
            <ul class="footer__list">
              <li class="list-item"><a href="#" class="list-item__link">Terms and Conditions</a></li>
              <li class="list-item"><a href="#" class="list-item__link">Privacy Policy</a></li>
              <li class="list-item"><a href="#" class="list-item__link">Privacy Policy</a></li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import NavBarSite from "../components/NavBarSite.vue";

export default {
  name: "IndexPage",
  components: { NavBarSite }
}
</script>
