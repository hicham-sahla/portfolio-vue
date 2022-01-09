<template>
  <q-layout view="lHh lpR lfr">
    <TheHeader></TheHeader>
    <TheAboutMe></TheAboutMe>
    <TheProjects></TheProjects>
    <TheFooter></TheFooter>
  </q-layout>
</template>

<script>
import TheHeader from "./components/layout/TheHeader.vue";
import TheAboutMe from "./components/layout/TheAboutMe.vue";
import TheProjects from "./components/layout/TheProjects.vue";
import TheFooter from "./components/layout/TheFooter.vue";

export default {
  name: "LayoutDefault",
  components: {
    TheHeader,
    TheAboutMe,
    TheProjects,
    TheFooter
  },
};
</script>
