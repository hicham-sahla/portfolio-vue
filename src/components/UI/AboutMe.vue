<template>
  <div class="row about-me text-white flex q-px-xl flex-center">
    <div class="col-md-6">
      <h2 class="text-center q-mt-xs bold">Wie ben ik?</h2>
      <p>
        Hey mijn naam is Hicham Sahla en ben 21 jaar oud. Sinds jongs af aan heb
        ik een passie voor alles wat te maken heeft met technologie en het
        internet. Vandaar dat ik in 2016 mijn carriere als webdeveloper, starte
        met de opleiding Media Development op het Mediacollege Amsterdam. Na een
        intensieve opleiding van drie jaar behaalde ik me Media development
        Diploma in 2019. Hierna ben ik in een tussenjaar als webdeveloper volle
        bak aan de slag gegaan. <br /><br />Tijdens het werken als professional
        merkte ik dat ik nog verder wou studeren en dat vooral het UI en UX
        aspect van websites en Apps me erg interesseerde. Hierdoor ben ik
        gestart met de opleiding Communications & Multimedia design aan de Hoge
        School van Amsterdam. Momenteel zit ik in mijn tweede jaar en merk ik
        dat mijn voorkeur uit gaat naar werk, waarbij ik als webdeveloper aan de
        slag kan gaan, met oog voor een goede UI en UX design.
      </p>
    </div>
  </div>
</template>

<script>
import Swiper from "swiper";
export default {
  name: "AboutMe",
  mounted() {
    new Swiper(".swiper-container", {
      slidesPerView: 4,
      grabCursor: true,
      paginationClickable: true,
    });
  },
};
</script>
