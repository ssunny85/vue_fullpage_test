<template>
  <div class="canvas">
    <Header></Header>
    <Body></Body>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Body from './components/Body.vue';
import Footer from './components/Footer.vue';
export default {
  name: 'app',
  components: { Header, Body, Footer },
}
</script>

<style lang="scss" src="./assets/scss/mw_style.scss" />
