<template>
  <section class="contact-section">
    <div class="auto-container">
      <div class="sec-title centered">
        <h2>Offices near you<span class="dot">.</span></h2>
      </div>

      <div class="upper-info">
        <div class="row clearfix">
          <div class="info-block col-xl-3 col-lg-6 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="0ms"
               data-wow-duration="1500ms">
            <div class="inner-box">
              <h5>Austin</h5>
              <div class="text">
                <ul class="info">
                  <li>22 Texas West Hills</li>
                  <li><a href="mailto:needhelp@linoor.com">needhelp@linoor.com</a></li>
                  <li><a href="tel:666888000">666 888 000</a></li>
                </ul>
              </div>
            </div>
          </div>

          <div class="info-block col-xl-3 col-lg-6 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="300ms"
               data-wow-duration="1500ms">
            <div class="inner-box">
              <h5>Boston</h5>
              <div class="text">
                <ul class="info">
                  <li>5 Federal Street Boston</li>
                  <li><a href="mailto:needhelp@linoor.com">needhelp@linoor.com</a></li>
                  <li><a href="tel:666888000">666 888 000</a></li>
                </ul>
              </div>
            </div>
          </div>

          <div class="info-block col-xl-3 col-lg-6 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="600ms"
               data-wow-duration="1500ms">
            <div class="inner-box">
              <h5>New york</h5>
              <div class="text">
                <ul class="info">
                  <li>8th Broklyn New York</li>
                  <li><a href="mailto:needhelp@linoor.com">needhelp@linoor.com</a></li>
                  <li><a href="tel:666888000">666 888 000</a></li>
                </ul>
              </div>
            </div>
          </div>

          <div class="info-block col-xl-3 col-lg-6 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="900ms"
               data-wow-duration="1500ms">
            <div class="inner-box">
              <h5>baltimore</h5>
              <div class="text">
                <ul class="info">
                  <li>3 Lombabr 50 Baltimore</li>
                  <li><a href="mailto:needhelp@linoor.com">needhelp@linoor.com</a></li>
                  <li><a href="tel:666888000">666 888 000</a></li>
                </ul>
              </div>
            </div>
          </div>

        </div>
      </div>

      <div class="map-box">
        <iframe class="map-iframe"
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d230899.1642407818!2d145.06327708904033!3d-37.792102974783376!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad65cd0db468a97%3A0xb61fde84306fc38a!2sMelbourne%20Zoo!5e0!3m2!1sen!2s!4v1592307685926!5m2!1sen!2s"
                style="border:0;" aria-hidden="false" tabindex="0"></iframe>
      </div>
      <div class="form-box">
        <div class="sec-title">
          <h2>Write Us a Message<span class="dot">.</span></h2>
        </div>
        <div class="default-form">
          <form method="post" action="#" id="contact-form">
            <div class="row clearfix">
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input type="text" name="username" value="" placeholder="Your Name" required="">
                </div>
              </div>
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input type="email" name="email" value="" placeholder="Email Address"
                         required="">
                </div>
              </div>
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input type="text" name="phone" value="" placeholder="Phone Number" required="">
                </div>
              </div>
              <div class="form-group col-lg-6 col-md-6 col-sm-12">
                <div class="field-inner">
                  <input type="text" name="subject" value="" placeholder="Subject" required="">
                </div>
              </div>
              <div class="form-group col-lg-12 col-md-12 col-sm-12">
                <div class="field-inner">
                  <textarea name="message" placeholder="Write Message" required=""></textarea>
                </div>
              </div>
              <div class="form-group col-lg-12 col-md-12 col-sm-12">
                <button class="theme-btn btn-style-one">
                  <i class="btn-curve"></i>
                  <span class="btn-title">Send message</span>
                </button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "ContactPage"
    }
</script>

<style scoped>

</style>
