<template>
  <q-page-container id="NavBar">
    <NavBar />
  </q-page-container>
  <q-page-container id="PageHeader">
    <PageHeader />
  </q-page-container>
    <q-page-container id="PageHeader">
    <PageHeader />
  </q-page-container>
</template>

<script>
import NavBar from "../UI/NavBar.vue";
import PageHeader from "../UI/PageHeader.vue";
export default {
  name: "TheHeader",
  components: {
    NavBar,
    PageHeader,
  },
};
</script>
<style scoped></style>
