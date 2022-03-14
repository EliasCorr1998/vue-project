<template>
  <div id="app">
    <HeaderComponent></HeaderComponent>
    <BannerComponent></BannerComponent>
    <CardsComponent></CardsComponent>
    <BackpackingComponent></BackpackingComponent>
    <AboutComponent></AboutComponent>
    <ImagesComponent></ImagesComponent>
    <FormularioComponent></FormularioComponent>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import BannerComponent from "./components/BannerComponent.vue";
import CardsComponent from "./components/CardsComponent.vue";
import BackpackingComponent from "./components/BackpackingComponent.vue";
import AboutComponent from "./components/AboutComponent.vue";
import ImagesComponent from "./components/ImagesComponent.vue";
import FormularioComponent from "./components/FormularioComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";

export default {
  name: "app",
  components: {
    HeaderComponent,
    BannerComponent,
    CardsComponent,
    BackpackingComponent,
    AboutComponent,
    ImagesComponent,
    FormularioComponent,
    FooterComponent,
  },
};
</script>

<style>
@import "./assets/css/base.css";
</style>