<template>
  <q-layout view="lHh lpR lfr">
    <TheHeader></TheHeader>
    <TheAboutMe></TheAboutMe>
    <TheProjects></TheProjects>
  </q-layout>
</template>

<script>
import TheHeader from "./components/layout/TheHeader.vue";
import TheAboutMe from "./components/layout/TheAboutMe.vue";
import TheProjects from "./components/layout/TheProjects.vue";

export default {
  name: "LayoutDefault",
  components: {
    TheHeader,
    TheAboutMe,
    TheProjects
  },
};
</script>
