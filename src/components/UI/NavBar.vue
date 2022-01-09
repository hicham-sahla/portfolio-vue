<template>
  <q-header
    :class="{ navbar_bg_primary: scrollPosition > 50 }"
    class="q-pa-md bg-white"
    height-hint="98"
  >
    <q-toolbar class="container p-5">
      <q-toolbar-title v-if="scrollPosition > 50">
        Hicham Sahla
      </q-toolbar-title>
      <q-toolbar-title v-else class="text-primary">
        Hicham Sahla
      </q-toolbar-title>
      <a v-if="scrollPosition > 50" target="_blank" href="https://files.hichamsahla.nl/cv-hichamsahla.pdf" class="btn btn-light">Bekijk mijn CV</a>
      <a v-else target="_blank" href="https://files.hichamsahla.nl/cv-hichamsahla.pdf" class="btn btn-primary">Bekijk mijn CV</a>
    </q-toolbar>
  </q-header>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      scrollPosition: null,
    };
  },
  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY;
    },
  },
  mounted() {
    window.addEventListener("scroll", this.updateScroll);
  },
};
</script>
