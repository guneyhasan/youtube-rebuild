<template>
 <div class="bg-gray-800">

  <top-navigation class="bg-gray-800 -mt-16"/>

  <all-page class="bg-gray-800"/>

 </div>
</template>

<script>
import TopNavigation from "@/components/top-navigation";
import AllPage from "@/components/all-page";
export default {
  components: {AllPage, TopNavigation}
}


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
