<template>

  <div>

    <section class="banner-section banner-one">
      <div class="left-based-text">
        <div class="base-inner">
          <div class="hours">
            <ul class="clearfix">
              <li><span>mon - fri</span></li>
              <li><span>9am - 7pm</span></li>
            </ul>
          </div>
          <div class="social-links">
            <ul class="clearfix">
              <li><a href="#"><span>Twitter</span></a></li>
              <li><a href="#"><span>Facebook</span></a></li>
              <li><a href="#"><span>Youtube</span></a></li>
            </ul>
          </div>
        </div>
      </div>

      <div class="banner-carousel">

        <no-ssr> <!-- important to add no-ssr-->
          <carousel :items="1">
        <!-- Slide Item -->
        <div class="slide-item">
          <div class="image-layer" style="background-image: url(/images/main-slider/banner-1.jpg);"></div>
          <div class="left-top-line"></div>
          <div class="right-bottom-curve"></div>
          <div class="right-top-curve"></div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">welcome to Brolab AR</div>
                  <h1>Create your<br>AR Campaign.</h1>
                  <div class="link-box">
                    <a class="theme-btn btn-style-one" href="#services-section">
                      <i class="btn-curve"></i>
                      <span class="btn-title">Discover More</span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Slide Item -->
        <div class="slide-item">
          <div class="image-layer" style="background-image: url(/images/main-slider/banner-2.jpg);"></div>
          <div class="left-top-line"></div>
          <div class="right-bottom-curve"></div>
          <div class="right-top-curve"></div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">welcome to Brolab AR</div>
                  <h1>Surprise your<br>Clients</h1>
                  <div class="link-box">
                    <a class="theme-btn btn-style-one" href="#services-section">
                      <i class="btn-curve"></i>
                      <span class="btn-title">Discover More</span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

          </carousel>
        </no-ssr>

      </div>
    </section>

  </div>

</template>

<script>

  export default {
    name: "Banner",
  }
</script>

<style scoped>

</style>
