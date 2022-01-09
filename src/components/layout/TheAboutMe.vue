<template>
  <q-page-container class="bg-primary " id="AboutMe">
    <AboutMe />
  </q-page-container>
    <q-page-container class="bg-primary " id="TimeLine">
    <TimeLine />
  </q-page-container>
  <q-page-container id="MySkills">
    <MySkills />
  </q-page-container>
</template>

<script>
import AboutMe from "../UI/AboutMe.vue";
import TimeLine from "../UI/TimeLine.vue";
import MySkills from "../UI/MySkills.vue";
export default {
  name: "TheAboutMe",
  components: {
    AboutMe,
    TimeLine,
    MySkills,
  },
};
</script>
<style scoped></style>
