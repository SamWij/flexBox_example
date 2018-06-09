<template>
  <div id="app">
    <Nav></Nav>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Nav from './components/Nav.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'app',
  components: {
    Nav, 
    Main, 
    Footer
  }
}
</script>