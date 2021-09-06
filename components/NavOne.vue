<template>
  <header class="header-one">
    <!-- Start top bar -->
    <div class="topbar-area">
      <div class="container">
        <div class="row">
          <div class=" col-md-8 col-sm-8 col-xs-12">
            <div class="topbar-left">
              <ul>
                <li><a href="#"><i class="fa fa-exclamation"></i> Stress test is on-going. Join the mayhem now!</a></li>
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
          <div class="col-md-2 col-sm-2">
            <div class="logo">
              <!-- Brand -->
              <a class="navbar-brand " href="/">
                <img src="/img/logo/logo2.png" alt="">
              </a>
            </div>
            <!-- logo end -->
          </div>
          <div class="col-md-10 col-sm-10">
            <div class="header-right-link">
              <!-- search option end -->
              <a class="s-menu" href="https://discord.gg/B2wYj4r" target="_blank">Join Discord</a>
            </div>


            <!-- mainmenu start -->
            <nav class="navbar navbar-default">
              <div class="collapse navbar-collapse" id="navbar-example">
                <div class="main-menu">
                  <ul class="nav navbar-nav navbar-right">
                    <li><a class="pagess" href="/">Home</a></li>
                    <li><a class="pagess" href="#">News</a>
                    <li><nuxt-link class="pagess" to="/play">How to Join</nuxt-link></li>
                    <li><nuxt-link class="pagess" to="#">Tools</nuxt-link>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/about">Server Configurator</nuxt-link></li>
                        <li><nuxt-link to="/team">team</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link to="/contact">Contact</nuxt-link></li>
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
                  <li><a class="pagess" href="/">Home</a></li>
                    <li><a class="pagess" href="#">News</a>
                    <li><nuxt-link class="pagess" to="/play">How to Join</nuxt-link></li>
                    <li><nuxt-link class="pagess" to="#">Tools</nuxt-link>
                      <ul class="sub-menu">
                        <li><nuxt-link to="/about">Server Configurator</nuxt-link></li>
                        <li><nuxt-link to="/team">team</nuxt-link></li>
                      </ul>
                    </li>
                    <li><nuxt-link to="/contact">Contact</nuxt-link></li>
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
