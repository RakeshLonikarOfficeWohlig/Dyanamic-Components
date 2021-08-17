<template>
  <div id="app">
    <nav>
      <ul class="ul">
        <li class="li">
          <router-link to="/" class="a">Home</router-link>
        </li><br>
        <li class="li">
          <router-link to="/about" class="a">About Us</router-link>
        </li><br>
        <li class="li">
          <router-link to="/contact" class="a">Contact Us</router-link>
        </li><br>
        <li class="li">
          <router-link to="/settings" class="set">Settings</router-link>
        </li>
      </ul>
    </nav>
  <router-view></router-view>
   
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
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
