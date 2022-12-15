<template>
    <main>
        <h1>Curriculum</h1>
        <CurriculumComponent/>
    </main>
</template>

<script>
import CurriculumComponent from "@/components/CurriculumComponent.vue";

export default {
  name: "CurriculumView",
  components: {
    CurriculumComponent,
  },
};
</script>
<style  scoped>
main h1 {
  height: 150px;
  width: 150px;
  color: black;
}
</style>