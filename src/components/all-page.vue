<template>
  <div class="flex justify-between">
    <all-page-left/>

    <all-page-right/>





  </div>
</template>

<script>
import AllPageLeft from "@/components/all-page-left";
import AllPageRight from "@/components/all-page-right";
export default {
  name: "all-page",
  components: {AllPageRight, AllPageLeft}
}
</script>

<style scoped>

</style>