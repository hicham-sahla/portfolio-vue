<template>
  <q-layout view="lHh lpR lfr">
    <TheHeader></TheHeader>
    <q-footer elevated class="bg-grey-8 text-white">
      <q-toolbar class="container">
        <q-toolbar-title>
          <div>Hicham Sahla</div>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script>
import TheHeader from "./components/layout/TheHeader.vue";

export default {
  name: "LayoutDefault",
  components: {
    TheHeader,
  },
};
</script>
