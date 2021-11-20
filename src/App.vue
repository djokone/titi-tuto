<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <ul>
    <li><a href="/home">Accueil</a></li>
    <li><a href="/blog">Blog</a></li>
    <li><a href="/contact">Contact</a></li>
  </ul>
  <h1 id="titreBlog" class="red">Titre d'importance 1</h1>
  <h2 class="">Titre d'importance 2</h2>
  <h3 class="red">Titre d'importance 3</h3>
  <p>
    mon <span class="gros">paragraphe</span> te text ou je peux raconter ma life
  </p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/Titan_in_true_color.jpg/220px-Titan_in_true_color.jpg" alt="">
</template>

<style>
body {

}
.red {
  color: red;
}
.gros {
  font-weight: bold;
}
#titreBlog {
  font-size: 30px;;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background: black; 
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
