<script>
import Header from "./components/Header.vue";
import Hero from "./components/Hero.vue";
import Menu from "./components/Menu.vue";
import RectlengeSection from "./components/RectlengeSection.vue";
import Product from "./components/Product.vue";
import DowloandMenu from "./components/DowloandMenu.vue";
export default {
  components: {
    Header,
    Hero,
    Menu,
    RectlengeSection,
    Product,
    DowloandMenu,
  }
}
</script>

<template>
  <header>
    <Header/>
  </header>
  <main>
    <Hero/>
    <Menu/>
    <RectlengeSection/>
    <Product/>
    <DowloandMenu/>
  </main>
</template>

