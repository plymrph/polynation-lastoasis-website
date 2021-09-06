<template>
  <header class="header-one">
    <!-- Start top bar -->
    <div class="topbar-area">
      <div class="container">
        <div class="row">
          <div class=" col-md-8 col-sm-8 col-xs-12">
            <div class="topbar-left">
              <ul>
                <li><a href="#"><i class="fa fa-envelope"></i> info@playdo4.com</a></li>
                <li><a href="#"><i class="fa fa-clock-o"></i> Live support</a></li>
              </ul>
            </div>
          </div>
          <div class="col-md-4 col-sm-4 col-xs-12">
            <div class="topbar-right">
              <ul>
                <li><a href="#"><img src="/img/icon/w1.png" alt="">English</a>
                  <ul>
                    <li><a href="#"><img src="/img/icon/w2.png" alt="">Deutsch</a></li>
                    <li><a href="#"><img src="/img/icon/w3.png" alt="">Español</a></li>
                    <li><a href="#"><img src="/img/icon/w4.png" alt="">Français</a></li>
                    <li><a href="#"><img src="/img/icon/w5.png" alt="">العربية</a></li>
                  </ul>
                </li>
                <li><a href="#"><img src="/img/icon/login.png" alt="">Login</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End top bar -->
    <!-- header-area start -->
    <div id="sticker" :class="`header-area hidden-xs ${sticky ? 'stick' : ''}`">
      <div class="container">
        <div class="row">
          <!-- logo start -->
          <div class="col-md-3 col-sm-3">
            <div class="logo">
              <!-- Brand -->
              <a class="navbar-brand " href="/">
                <img src="/img/logo/logo2.png" alt="">
              </a>
            </div>
            <!-- logo end -->
          </div>
          <div class="col-md-9 col-sm-9">
            <div class="header-right-link">
              <!-- search option end -->
              <nuxt-link class="s-menu" to="/login">Join now</nuxt-link>
            </div>


            <!-- mainmenu start -->
            <nav class="navbar navbar-default">
              <div class="collapse navbar-collapse" id="navbar-example">
                <div class="main-menu">
                  <ul class="nav navbar-nav navbar-right">
                    <li><a class="pagess" href="/">Home</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/">Home 01</nuxt-link></li>
                        <li><nuxt-link to="/index-2">Home 02</nuxt-link></li>
                        <li><nuxt-link to="/index-3">Home 03</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link class="pagess" to="/play">Play</nuxt-link></li>
                    <li><nuxt-link class="pagess" to="#">Games</nuxt-link>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/games">All Games</nuxt-link></li>
                        <li><nuxt-link to="/games-details">Games Details</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link class="pagess" to="/lottery">Lottery</nuxt-link></li>
                    <li><nuxt-link class="pagess" to="#">Pages</nuxt-link>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/about">About</nuxt-link></li>
                        <li><nuxt-link to="/team">team</nuxt-link></li>
                        <li><nuxt-link to="/faq">FAQ</nuxt-link></li>
                        <li><nuxt-link to="/pricing">Pricing</nuxt-link></li>
                        <li><nuxt-link to="/login">Login</nuxt-link></li>
                        <li><nuxt-link to="/signup">Signup</nuxt-link></li>
                        <li><nuxt-link to="/error">Error</nuxt-link></li>
                        <li><nuxt-link to="/terms">terms & Conditions</nuxt-link></li>
                      </ul>
                    </li>
                    <li><a class="pagess" href="#">Blog</a>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/blog">Blog grid</nuxt-link></li>
                        <li><nuxt-link to="/blog-sidebar">Blog Sidebar</nuxt-link></li>
                        <li><nuxt-link to="/blog-details">Blog Details</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link to="/contact">contacts</nuxt-link></li>
                  </ul>
                </div>
              </div>
            </nav>
            <!-- mainmenu end -->
          </div>

        </div>
      </div>
    </div>
    <!-- header-area end -->
    <!-- mobile-menu-area start -->
    <div class="mobile-menu-area hidden-lg hidden-md hidden-sm">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="mobile-menu">
              <div class="logo">
                <a href="/index"><img src="/img/logo/logo2.png" alt="" /></a>
              </div>
              <div @click="mobileToggle = !mobileToggle" id="menu-button" class="menu-button"><i class="fa fa-bars"></i></div>
              <nav id="dropdown">
                <ul :style="`display: ${mobileToggle ? 'block' : 'none'}`">
                  <li><a class="pagess" href="index">Home</a>
                    <ul class="sub-menu">
                      <li><a href="/index">Home 01</a></li>
                      <li><a href="/index-2">Home 02</a></li>
                      <li><a href="/index-3">Home 03</a></li>
                    </ul>
                  </li>
                  <li><a class="pagess" href="play">Play</a></li>
                  <li><a class="pagess" href="#">Games</a>
                    <ul class="sub-menu">
                      <li><a href="/games">All Games</a></li>
                      <li><a href="/games-details">Games Details</a></li>
                    </ul>
                  </li>
                  <li><a class="pagess" href="lottery">Lottery</a></li>
                  <li><a class="pagess" href="#">Pages</a>
                    <ul class="sub-menu">
                      <li><a href="/about">About</a></li>
                      <li><a href="/team">team</a></li>
                      <li><a href="/faq">FAQ</a></li>
                      <li><a href="/pricing">Pricing</a></li>
                      <li><a href="/login">Login</a></li>
                      <li><a href="/signup">Signup</a></li>
                      <li><a href="/error">Error</a></li>
                      <li><a href="/terms">terms & Conditions</a></li>
                    </ul>
                  </li>
                  <li><a class="pagess" href="#">Blog</a>
                    <ul class="sub-menu">
                      <li><a href="/blog">Blog grid</a></li>
                      <li><a href="/blog-sidebar">Blog Sidebar</a></li>
                      <li><a href="/blog-details">Blog Details</a></li>
                    </ul>
                  </li>
                  <li><a href="/contact">contacts</a></li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- mobile-menu-area end -->
  </header>
</template>

<script>
    export default {
      name: "NavOne",
      data(){
        return {
          sticky: false,
          mobileToggle: false
        }
      },
      mounted() {
        window.addEventListener('scroll', this.handleScroll);
      },
      methods: {

        handleScroll() {
          if (window.scrollY > 70) {
            this.sticky = true
          } else if (window.scrollY < 70) {
            this.sticky = false
          }
        },
      }


    }
</script>

<style scoped>

</style>
