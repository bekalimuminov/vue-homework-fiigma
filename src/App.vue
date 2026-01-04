<script>
import Header from "./components/Header.vue";
import Hero from "./components/Hero.vue";
import Menu from "./components/Menu.vue";
import RectlengeSection from "./components/RectlengeSection.vue";
import Product from "./components/Product.vue";
export default {
  components: {
    Header,
    Hero,
    Menu,
    RectlengeSection,
    Product,
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
  </main>
</template>

