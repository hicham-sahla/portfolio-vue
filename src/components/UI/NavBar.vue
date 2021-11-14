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
      <q-btn
        v-if="scrollPosition > 50"
        rounded
        outline
        color="white"
        no-caps
        size="lg"
        icon-right="article"
        label="Bekijk me CV"
      />
      <q-btn
        v-else
        rounded
        outline
        color="primary"
        no-caps
        size="lg"
        icon-right="article"
        label="Bekijk me CV"
      />
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