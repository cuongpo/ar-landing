<template>
  <section class="sponsors-section">
    <div class="sponsors-outer">
      <!--Sponsors-->
      <div class="auto-container">
        <!--Sponsors Carousel-->
        <div class="sponsors-carousel">
          <no-ssr>
          <carousel :items="5" :autoplay="true" :responsive="{0: {items: 1},640: {items: 2},992: {items: 3},1024: {items: 5}}">
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          <div class="slide-item">
            <figure class="image-box"><a href="#"><img src="/images/clients/7.png" alt=""></a></figure>
          </div>
          </carousel>
          </no-ssr>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "BrandsSection"
    }
</script>

<style scoped>

</style>
