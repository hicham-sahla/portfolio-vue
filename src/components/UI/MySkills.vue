<template>
  <div class="row my-skills flex q-px-xl flex-center">
    <div class="col-md-8">
      <div bordered class="row shadow-5 card q-pa-lg rounded bg-white">
        <div class="col-md-4 q-pa-md text-center">
          <img
            src="../../assets/designer.svg"
            class="img-fluid img-center q-mb-md"
            alt="designer icon"
          />
          <h5 class="q-mt-xs bold">Design</h5>
          <p class="text-left">
            Ik waardeer simpele content, structuur en duidelijke design
            patterns, waarbij er goed is nagedacht over de interacties.
          </p>
          <h7 class="text-center text-primary"
            >Dingen die ik leuk vind om te designen</h7
          >
          <p>UX, UI, Web, Mobile, Apps</p>
          <q-list class="text-center">
            <h7 class="text-center text-primary">Design Tools:</h7>
            <q-item>
              <q-item-section> Adobe XD </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Adobe Illustrator </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Adobe Photoshop </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Adobe Rush </q-item-section>
            </q-item>
          </q-list>
        </div>
        <div class="col-md-4 q-pa-md text-center">
          <img
            src="../../assets/frontend.svg"
            class="img-fluid img-center q-mb-md"
            alt="frontend icon"
          />
          <h5 class="q-mt-xs bold">Webdevelopment</h5>
          <p class="text-left">
            Ik hou er van om te programmeren van scratch, om vervolgens op maat
            de mooiste ideeën tot leven te wekken. (In de browser natuurlijk!)
          </p>
          <h7 class="text-center text-primary">Skills & Experiences</h7>
          <p>HTML, CSS, Javascript, SASS/LESS, VUE 3, PHP, SQL, WordPress</p>
          <q-list class="text-center">
            <h7 class="text-center text-primary">Dev Tools:</h7>
            <q-item>
              <q-item-section> Terminal </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Node Package Manager </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> GIT </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Bootstrap 4/5 </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Quasar </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Vue CLI </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> PHP MyAdmin</q-item-section>
            </q-item>
          </q-list>
        </div>
        <div class="col-md-4 q-pa-md text-center">
          <img
            src="../../assets/browsercloud.svg"
            class="img-fluid img-center q-mb-md"
            alt="browser cloud icon"
          />
          <h5 class="q-mt-xs bold">Tech</h5>
          <p class="text-left">
            Buiten het programmeren en uitwerken van websites, vind ik het ook
            interessant om websites zoveel mogelijk buiten de code om te
            optimaliseren.
          </p>
          <h7 class="text-center text-primary">Kennis van</h7>
          <p>SEO, Structured Data, Image optimalisation, DNS/Hosting Tuning</p>
          <q-list class="text-center">
            <h7 class="text-center text-primary">Bekende termen en tools</h7>
            <q-item>
              <q-item-section> LightHouse </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Schema.org </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Caching </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> CDN (CloudFlare) </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Postmark </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Minification </q-item-section>
            </q-item>
            <q-item>
              <q-item-section> Semrush </q-item-section>
            </q-item>
          </q-list>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MySkills",
};
</script>
