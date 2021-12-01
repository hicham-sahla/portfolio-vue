<template>
  <div class="row my-skills flex q-px-xl q-py-xl flex-center">
    <div class="col-12">
      <h2 class="text-center">Recente projecten</h2>
      <p class="text-center">
        Hier zijn een aantal projecten waar ik aan mee heb kunnen werken.
      </p>
    </div>
    <div class="col-md-10">
      <div bordered class="row">
        <q-card class="my-card col-4">
          <q-img src="../../assets/mockuper.png">
            <div class="overlay">
              <div class="text">
                <h6 class="q-mb-none">Portfolio website</h6>
                <p>Mijn eigen persoonlijke portfolio website</p>
                <div class="skills-used">      
                  Vue.JS / HTML5 / SCSS     
                </div>
                <br />
                <a href="" class=" btn">Bekijk website</a>
              </div>
            </div>
          </q-img>
        </q-card>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Projects",
  data() {
    return {
      hover: false,
    };
  },
};
</script>
