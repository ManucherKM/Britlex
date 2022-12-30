<template>
  <div class="parent">
    <NavBarSite />

    <main class="parent__main container">
      <div class="parent__header">
        <div class="header__left">
          <h1 class="header__title">
            Learn <span class="header__span"></span> Any Foreign Language
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
          <div class="grid__speaking mt-ten">
            <div class="grid__container">
              <img src="../assets/img/speaking-img.png" alt="Photo" class="speaking__img">
              <div class="grid__block-text">
                <h3 class="block-text__title title-h2">Speaking</h3>
                <p class="block-text__subtitle w-100">Improve your English skills and confidence.
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
              <div class="block-right__writing mt-ten">
                <div class="grid__container">
                  <img src="../assets/img/writing.png" alt="Photo" class="speaking__img">
                  <div class="grid__block-text">
                    <h3 class="block-text__title title-h2">Writing</h3>
                    <p class="block-text__subtitle w-100">One of the most important and extensive
                      areas of natural science, the science that
                      studies substances, also their composition
                    </p>
                    <button class="btn btn-dark block-text__btn">Learn more</button>
                  </div>
                </div>
              </div>
              <div class="block-right__reading mt-ten">
                <div class="grid__container">
                  <img src="../assets/img/reading.png" alt="Photo" class="speaking__img">
                  <div class="grid__block-text">
                    <h3 class="block-text__title title-h2">Reading</h3>
                    <p class="block-text__subtitle w-100">perception and response actions of the user
                      resulting from the use and/or upcoming use
                      of the product, system or service
                    </p>
                    <button class="btn btn-dark block-text__btn">Learn more</button>
                  </div>
                </div>
              </div>
            </div>
            <div class="block-right__bottom mt-ten">
              <div class="bottom__listening">
                <div class="grid__container">

                  <div class="grid__block-text">
                    <div class="block-text__pad">
                      <h3 class="block-text__title title-h2">Listening</h3>
                      <p class="block-text__subtitle w-100">Here you can find activities to practise
                        your listening skills. Listening will help you
                        to improve your understanding
                      </p>
                      <button class="btn btn-dark block-text__btn btn-m-0">Learn more</button>
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
          <img src="../assets/img/about-us-img.png" alt="Photo" class="block-right__img-none">
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
            <img src="../assets/img/live-classes.png" alt="Photo" class="block-flex-img block-flex-img-center">
            <h3 class="block-flex__title title-h2">Live online classes</h3>
            <p class="block-flex__subtitle subtitle">
              Interactive group classes with expert
              teachers. Free 7-day trial
            </p>
            <div class="block-flex__price text-center mar-top transform-two">
              <p class="price-text"><span class="price">£12.99</span> per month</p>
            </div>
          </div>
          <div class="block-flex-one block-flex-one-tran">
            <img src="../assets/img/personal-tutorial.png" alt="Photo" class="block-flex-img">
            <h3 class="block-flex__title title-h2 mar-none">Personal Tuition</h3>
            <p class="block-flex__subtitle subtitle">
              Online one-to-one English tutoring – enjoy
              our first session for only $1
            </p>
            <div class="block-flex__price text-center transform-three">
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
import NavBarSite from './components/NavBarSite.vue';
</script>

<style lang="scss">
* {
  font-family: 'Poppins', sans-serif;
}

body {
  background: #fff;
}

.text-center {
  margin: 0 auto;
}

.container {
  max-width: 1340px;
}

.title-h1 {
  font-weight: 600;
  font-size: 30px;
  color: #000;
}

.title-h2 {
  font-weight: 600;
  font-size: 20px;
  color: #000;
}

.subtitle {
  font-weight: 400;
  font-size: 20px;
  color: #8F95A5;
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
  cursor: default;
}

.navbar {
  margin-top: 55px;

  .container-ul {
    width: 63%;
    justify-content: space-between;
  }

  .navbar-collapse {
    flex-grow: 0;
  }

  ul {
    font-weight: 500;
    font-size: 20px;
  }

  .btn {
    border: 2px solid #000;
    background: rgba(255, 255, 255, 0);
    padding: 17px 57px;
    font-size: 24px;
  }
}

.parent__header {
  margin-top: 51px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 147px;

  .header__title {
    font-size: 64px;
    font-weight: 600;
    width: 386px;
    margin-bottom: 40px;
    position: relative;
  }

  .header__span {
    padding-left: 70px;
  }

  .header__title::after {
    content: "";
    position: absolute;
    top: 40%;
    right: -40%;
    width: 85px;
    height: 85px;
    background-image: url("../img/lampa.svg");
    background-position: 50% 50%;
    background-repeat: no-repeat;
  }

  .header__subtitle {
    width: 521px;
    margin-bottom: 61px;
  }

  .left__btn {
    padding: 32px 117px;
    border-radius: 15px;
    font-size: 36px;
  }
}

.parent__skills {
  margin-bottom: 252px;

  h2 {
    margin-bottom: 92px;
  }

  .skills__grid {
    display: grid;
    grid-template-columns: 1fr 2fr;
    grid-column-gap: 20px;
  }

  .grid__container {
    background: #F5F5F5;
    border-radius: 0.8em;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100%;
  }

  .block-text__title {
    margin-top: 5px;
    margin-bottom: 20px;
  }

  .block-text__subtitle {
    font-size: 16px;
    color: #8F95A5;
    width: 360px;
  }

  .block-text__btn {
    font-weight: 500;
    font-size: 18px;
    padding: 17px 64px;
  }

  .grid__block-right {
    display: grid;
    grid-template-rows: 2fr 1fr;
    grid-row-gap: 20px;
    height: min-content;
  }

  .block-right__top {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-column-gap: 20px;
  }

  .block-right__reading .block-text__title {
    margin-top: 52px;
  }

  .block-right__bottom {
    height: min-content;

    .grid__block-text {
      padding: 44px 0;
      display: flex;
      justify-content: space-between;
    }
  }

}

.parent__about-us {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 222px;

  .about-us__title {
    margin-bottom: 23px;
  }

  .about-us__subtitle {
    width: 635px;
    margin-bottom: 42px;
  }

  .about-us__block-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}

.parent__pricing {
  margin-bottom: 136px;

  .pricing__title {
    margin-bottom: 71px;
  }

  .block-flex__title {
    margin: 40px 0 20px 0;
  }

  .block-flex__subtitle {
    margin: 20px 0 30px 0;
    width: 418px;
  }

  .block-flex__price {
    background: #EEEEEE;
    border-radius: 5px;
    width: 240px;
    margin-left: 0;
    margin-right: 0;

    .price-tex {
      font-size: 18px;
      color: #546269;
    }

    .price {
      font-size: 30px;
      margin-right: 8px;
    }
  }

  .pricing__block-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .mar-top {
    transform: translateY(62%);
  }
}

.parent__contact-us {
  margin-bottom: 180px;

  .contact-us__container-flex {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }

  .right__title {
    font-size: 36px;
    margin-bottom: 20px;
  }

  .right__subtitle {
    width: 445px;
    font-size: 16px;
    font-weight: 400;
    color: #8F95A5;
    margin-bottom: 36px;
  }

  .right__block-input {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 105%;
  }

  .block-input__input {
    border: 1px solid #8F95A5;
    outline: none;
    width: 323px;
    height: 60px;
    border-radius: 0.7em;
    color: #8F95A5;
  }

  .block-input__input[type=text] {
    font-size: 14px;
    padding-left: 38px;
    font-weight: 400;
  }

  .block-input__btn {
    border-radius: 0.7em;
    padding: 18px 56px;
  }
}


.parent__footer {
  .container {
    border-top: 1px solid #C4C4C4;
  }

  .footer-flex {
    margin-top: 23px;
    padding-bottom: 23px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .footer__block-right {
    .footer__list {
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 0;
      padding: 0;

      li {
        list-style: none;
        margin-left: 15px;
      }

      .list-item__link {
        text-decoration: none;
        color: #8F95A5;
      }
    }
  }
}

.block-right__img-none {
  display: none;
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0);
  border: none;
}

@media (max-width: 767px) {
  .container {
    max-width: 700px;
    padding: 0;
  }

  .subtitle {
    font-size: 16px;
  }

  .parent__header {
    margin-bottom: 56px;

    .header__title {
      font-size: 36px;
      width: 230px;
    }

    .header__subtitle {
      width: 338px;
    }

    .left__btn {
      padding: 19px 67px;
      font-size: 18px;
      border-radius: 5px;
    }

    .header__img {
      width: 352px;
      height: 352px;
    }
  }

  .parent__skills {
    margin-bottom: 52px;

    h2 {
      margin-bottom: 37px;
      width: 241px;
    }

    .skills__grid {
      grid-template-columns: 30% 60%;
      grid-column-gap: 10px;
    }

    .block-text__subtitle {
      font-size: 13px;
      width: 194px;
    }

    .block-text__btn {
      font-size: 16px;
      padding: 14px 42px;
    }

    .speaking__img {
      width: 100%;
    }

    .grid__block-text {
      padding: 0 16px;
    }

    .block-right__top {
      grid-column-gap: 10px;
    }

    .grid__block-right {
      grid-row-gap: 10px;
      grid-template-rows: 465px 1fr;
    }

    .block-text__pad {
      padding-left: 16px;
    }

    .block-right__bottom {
      .grid__block-text {
        padding: 22px 0;

      }
    }

    .skills__grid {
      transform: translateX(10px);
    }
  }

  .parent__about-us {
    margin-bottom: 84px;

    .about-us__subtitle {
      font-size: 14px;
      width: 321px;
    }

    .title-h1 {
      font-size: 22px;
    }

    .about-us__block-flex {
      .subtitle {
        font-size: 13px;
      }
    }

    .block-right__img {
      width: 295px;
      height: 295px;
    }
  }

  .parent__pricing {
    margin-bottom: 65px;

    .block-flex-one {
      width: 197px;
    }

    .pricing__title {
      margin-bottom: 31px;
    }

    .block-flex-img {
      width: 100%;
      height: auto;
    }

    .subtitle {
      font-size: 14px;
      width: 100%;
    }

    .title-h2 {
      margin: 23px 0 15px 0;
    }

    .price {
      font-size: 22px;
    }

    .block-flex__price {
      width: 100%;
    }

    .block-flex-img-center {
      margin-top: 12px;
    }

    .mar-none {
      margin: 0;
    }

    .transform-two {
      transform: translateY(44px);
    }

    .transform-three {
      transform: translateY(36px);
    }
  }

  .parent__contact-us {
    margin-bottom: 112px;

    .left__img {
      width: 233px;
      height: auto;
    }

    .right__title {
      width: 169px;
      font-size: 30px;
    }

    .right__subtitle {
      width: 389px;
    }

    .block-input__input {
      width: 283px;
    }

    .block-input__btn {
      padding: 15px 40px;
    }
  }
}

@media (max-width: 320px) {
  .container {
    max-width: 320px;
    padding: 0 15px;
  }

  .title-h1 {
    font-size: 24px;
  }



  .parent__header {
    flex-direction: column;
    justify-content: center;
    margin-bottom: 50px;

    .header__title::after {
      display: none;
    }

    .skills__grid {
      display: block;
    }

    .header__title {
      width: 100%;
      text-align: center;
      font-size: 24px;
      margin-bottom: 20px;
    }

    .header__span {
      display: none;
    }

    .header__subtitle {
      width: 100%;
      text-align: center;
      margin-bottom: 35px;
    }

    .left__btn {
      width: 100%;
      font-size: 16px;
    }

    .header__right {
      order: -1;

      img {
        width: 299px;
        height: auto;
      }
    }


  }

  .skills__grid {
    transform: translateX(0) !important;
    display: block !important;

    .grid__block-right {
      display: block;
    }

    .block-right__top {
      display: block;
    }
  }

  .navbar {
    margin-top: 36px;
    padding: 0;

    .navbar-brand {
      img {
        width: 71px;
        height: auto;
      }
    }
  }

  .mt-ten {
    margin-bottom: 20px !important;
  }

  .mt-ten:last-of-type {
    margin-bottom: 0;
  }

  .block-text__btn {
    margin-bottom: 25px;
  }

  .block-text__subtitle {
    width: 100%;
  }

  .grid__block-text {
    flex-direction: column;

    .btn-m-0 {
      margin: 0;
    }

    .block-text__pad {
      order: 1;
      margin-top: 20px;
    }
  }

  .about-us__block-right {
    display: none;
  }

  .block-right__img-none {
    display: block;
    width: 95%;
    height: auto;
  }

  .about-us__subtitle {
    width: 100% !important;
    text-align: center;
  }

  .about-us__block-flex {
    flex-direction: column;
  }

  .parent__pricing {
    .pricing__block-flex {
      flex-direction: column;

      .block-flex-one {
        width: 100%;
      }

      .transform-two {
        transform: translateY(0);
      }

      .transform-three {
        transform: translateY(0);
      }
    }
  }

  .parent__contact-us {
    margin-bottom: 60px;

    .contact-us__container-flex {
      flex-direction: column;
    }

    .right__title {
      width: 100%;
    }

    .right__subtitle {
      width: 100%;
    }

    .right__block-input {
      flex-direction: column;

    }

    .block-input__input {
      width: 100%;

    }

    .block-input__input[type="text"] {
      padding-left: 20px;
    }

    .block-input__btn {
      width: 100%;
      margin-top: 17px;
    }

  }

  .parent__footer {
    .navbar-brand {
      img {
        width: 71px;
        height: 36px;
      }
    }

    .footer-flex {
      flex-direction: column;
    }

    .list-item__link {
      font-size: 11px;
      white-space: nowrap;
    }

    .footer__list {
      margin-top: 15px !important;
    }

    .list-item {
      margin-left: 10px !important;
    }
  }
}
</style>