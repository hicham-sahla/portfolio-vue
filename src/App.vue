<template>
  <q-layout view="lHh lpR lfr">
    <TheHeader></TheHeader>
    <TheAboutMe></TheAboutMe>
  </q-layout>
</template>

<script>
import TheHeader from "./components/layout/TheHeader.vue";
import TheAboutMe from "./components/layout/TheAboutMe.vue";

export default {
  name: "LayoutDefault",
  components: {
    TheHeader,
    TheAboutMe
  },
};
</script>
