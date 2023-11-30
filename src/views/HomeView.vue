<script setup>
import GeneralContent from "../components/GeneralContent.vue";
import SectionOne from "../components/SectionOne.vue";
import SectionTwo from "../components/SectionTwo.vue";
</script>

<template>
  <main>
    <GeneralContent />
    <h3>Key Features of Alpha Ecosystem</h3>
    <div>
      <SectionOne />
      <SectionTwo />
    </div>
  </main>
</template>
<style lang="scss" scoped>
main {
  background-color: #c8c2c2;
}
div {
  text-align: center;
  padding: 2%;
  display: flex;
}
h3 {
  padding: 10%;
  color: #21568c;
  text-align: center;
}
</style>
