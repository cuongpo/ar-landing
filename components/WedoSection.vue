<template>
  <section class="we-do-section" id="benefit-section">
    <div class="auto-container">
      <div class="row clearfix">
        <!--Left Column-->
        <div class="left-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner">
            <div class="sec-title">
              <h2>The power of augmented reality<span class="dot">.</span></h2>
            </div>
           
              
              <div class="text">Brolab AR helps brands and creative agencies to build, publish, analyze, and scale engaging marketing campaigns
across their complete customer journey. It’s as easy as that!.</div>
            
            
          </div>
        </div>

        <!--Right Column-->
        <div class="right-col col-lg-6 col-md-12 col-sm-12">
          <div class="inner">
            <div class="faq-box">
              <div class="accordion-container-one">
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">More engaging marketing campaigns</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">Create more powerful, immersive and memorable marketing campaigns that blow minds, light-up faces and get shared the world over.</p>
                  </div>
                </div>
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">Boost sales and give content an extra gear</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">Make your off- and online sales more effective, thanks to immersive AR experiences that take content creation to the next level.</p>
                  </div>
                </div>
                <div class="ac">
                  <h2 class="ac-q accordion__title-text" tabIndex="0">Close the gap between off- and online</h2>
                  <div class="ac-a accordion__content">
                    <p class="accordion__content-desc">Finally, get ROI and metrics even from offline communication! Track your audience and get ready to reach for the sky.</p>
                  </div>
                </div>

              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
      name: "WedoSection",
      mounted() {
        new Accordion('.accordion-container-one');
      }

    }
</script>

<style scoped>
  .ac {
    margin-top: 10px;
    padding: 10px;
    background: #fff;
    box-sizing: border-box;
  }

  .ac>.ac-q {
    font: bold 15px Arial, sans-serif;
    font-size: 20px;
    color: #444;
    padding: 10px 30px 10px 10px;
    margin: 0;
    text-decoration: none;
    display: block;
    cursor: pointer;
    position: relative;
    font-weight: 500;
    text-transform: uppercase;
    font-family: Teko;
  }

  .ac.is-active .ac-q {
    color: #FFAA17 !important;
  }
  .ac>.ac-q::after {
    content: '+';
    text-align: center;
    width: 15px;
    right: 10px;
    top: 50%;
    -webkit-transform: translate(0, -50%);
    transform: translate(0, -50%);
    position: absolute
  }

  .ac>.ac-a {
    overflow: hidden;
    -webkit-transition-property: all;
    transition-property: all;
    -webkit-transition-timing-function: ease;
    transition-timing-function: ease
  }

  .ac>.ac-a p {
    font: 16px/1.5 Arial, sans-serif;
    color: #444;
    margin: 0;
    padding: 10px
  }

  .ac.js-enabled>.ac-a {
    visibility: hidden
  }

  .ac.is-active>.ac-a {
    visibility: visible
  }

  .ac.is-active>.ac-q::after {
    content: '\2013';
    color: #FFAA17;
  }

  .progress-bar {
    width: 100%;
    background-color: #e0e0e0;
    padding: 3px;
    border-radius: 3px;
    box-shadow: inset 0 1px 3px rgba(0, 0, 0, .2);
  }

  .progress-bar-fill {
    display: block;
    height: 7px;
    background-color: #FFAA17;
    border-radius: 3px;

    transition: width 500ms ease-in-out;
  }
</style>

