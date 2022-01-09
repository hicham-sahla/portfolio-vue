<template>
  <div class="row text-white flex q-px-xl flex-center timeline-row">
    <div class="col-md-12 timeline-col swiper-container">
        <div class="swiper-wrapper timeline">
          <div class="swiper-slide">
            <div class="timestamp">
              <span class="date">April 2016</span>
            </div>
            <div class="status">
              <small>Start opleiding mediadevelopment</small>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="timestamp">
              <span class="date"> September 2018</span>
            </div>
            <div class="status">
              <small>Start stage als front-end developer<br> bij Activate your Business B.V.</small>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="timestamp">
              <span class="date">Februari 2019</span>
            </div>
            <div class="status">
              <small>Start stage App developer<br> Bij Activate your Business B.V.</small>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="timestamp">
              <span class="date">Juli 2019</span>
            </div>
            <div class="status">
              <small>Diploma Media development behaald, op het<br> Mediacollege Amsterdam</small>
            </div>
          </div>
          <div class="swiper-slide">
            <div class="timestamp">
              <span class="date">Augustus 2019</span>
            </div>
            <div class="status">
              <small>Als webdeveloper aan de slag bij<br> Activate your Business B.V.</small>
            </div>
          </div>
           <div class="swiper-slide">
            <div class="timestamp">
              <span class="date">September 2020</span>
            </div>
            <div class="status">
              <small>Start opleiding CMD bij de<br> Hoge School van Amsterdam</small>
            </div>
          </div>
        </div>
      </div>
  </div>
  
    

</template>

<script>
  import Swiper from 'swiper';
export default {
  name: "TimeLine",
    mounted() {
   new Swiper('.swiper-container', {
      slidesPerView: 4,
      grabCursor: true,
      paginationClickable: true,
    });    
  }
};
</script>
