<template>
  <div>
    <div class="preloader">
      <div class="lds-ripple">
        <div></div>
        <div></div>
      </div>
    </div>

    <header class="main-nav__header-one ">
      <nav class="header-navigation stricky">
        <div class="container">
          <!-- Brand and toggle get grouped for better mobile display -->
          <div class="main-nav__logo-box">
            <a href="/" class="main-nav__logo">
              <img src="/assets/images/logo-1-1.png" width="105" alt="Awesome Image" />
            </a>
            <a href="#" class="side-menu__toggler"><i class="fa fa-bars"></i>
              <!-- /.smpl-icon-menu --></a>
          </div><!-- /.logo-box -->
          <!-- Collect the nav links, forms, and other content for toggling -->
          <div class="main-nav__main-navigation">
            <ul class="one-page-scroll-menu main-nav__navigation-box">
              <li class="current scrollToLink">
                <a href="#banner">Home</a>
              </li>
              <li class="scrollToLink">
                <a href="#features">Features</a>
              </li>
              <li class="scrollToLink">
                <a href="#pricing">Pricing</a>
              </li>
              <li class="scrollToLink">
                <a href="#app-shots">App Screens</a>
              </li>
              <li class="scrollToLink">
                <a href="#testimonials">Testimonials</a>
              </li>
              <li class="dropdown scrollToLink">
                <a href="#blog">Blog</a>
                <ul>
                  <li><nuxt-link to="/blog">Blog Page</nuxt-link></li>
                  <li><nuxt-link to="/blog-details">Blog Details</nuxt-link></li>
                </ul><!-- /.sub-menu -->
              </li>
              <li class="scrollToLink">
                <a href="#contact">Contact</a>
              </li>
            </ul>
          </div><!-- /.navbar-collapse -->
          <div class="main-nav__right">
            <a href="#contact" data-target="#contact" class="thm-btn header__btn scroll-to-target">Start Trial</a><!-- /.thm-btn header__btn -->
          </div><!-- /.main-nav__right -->
        </div>
        <!-- /.container -->
      </nav>
    </header>
  </div>
</template>

<script>
    export default {
      name: "Header"
    }
</script>

<style scoped>

</style>
