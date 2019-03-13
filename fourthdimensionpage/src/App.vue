<template>
  <div id="app">
    <fourthdimension-navbar></fourthdimension-navbar>
    <fourthdimension-header></fourthdimension-header>
    <hr>
    <fourthdimension-games></fourthdimension-games>
    <hr>
    <fourthdimension-assets></fourthdimension-assets>
    <hr>
    <fourthdimension-contact></fourthdimension-contact>
    <fourthdimension-footer></fourthdimension-footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import Games from './components/Games.vue'
import Assets from './components/Assets.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  components: {
    'fourthdimension-navbar': Navbar,
    'fourthdimension-header': Header,
    'fourthdimension-games': Games,
    'fourthdimension-assets': Assets,
    'fourthdimension-contact': Contact,
    'fourthdimension-footer': Footer,
  }
}
</script>

<style>
body {
  font-family: 'Montserrat', sans-serif;
  line-height: 1;
  background: black;
  color: #fff;
  text-align: center;
}

hr {
  border: 1px solid rgba(255, 255, 255, .1);
}
</style>
