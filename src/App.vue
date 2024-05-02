<template>
  <NavbarElement></NavbarElement>
  <HomeView></HomeView>
  <FooterElement></FooterElement>
</template>
<script>
import HomeView from "@/views/HomeView.vue";
import FooterElement from "@/components/FooterElement.vue";
import NavbarElement from "./components/NavbarElement.vue";
export default {
  components: {
    HomeView,
    FooterElement,
    NavbarElement,
   
  }
}
</script>
<style>
  
</style>