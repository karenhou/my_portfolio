<template>
  <div id="app">
    <app-navbar></app-navbar>
    <router-view/>
    <footer class="footer py-5">
      <div class="container">
        <div class="row">
          <div class="col text-muted">
            <p><span><a href="https://icons8.com">Icon pack by Icons8</a> & <a href="https://commons.wikimedia.org/wiki/File:Vue.js_Logo.svg">via Wikimedia Commons</a></span></p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'

export default {
  name: 'App',
  data() {
    return {

    }
  },
  components: {
    appNavbar: Navbar
  }
}
</script>

<style>
.footer {
  background: #41B983;
  color:white;
}
</style>
