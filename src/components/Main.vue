<template>
  <div>
  <header>
    <img class="logo" src="https://3axis.co/user-images/eo2gkl18.png">
    <h1 class="titulo"> {{title}}</h1>
    <button v-on:click="subscribir"> Subscribite </button>
  </header>
    <div id="contenedor">
    <p class="subtitulo"> El verdadero sabor a café ·······································································································</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
  data () {
    return  {
      title: "Tienda Café"
    }
  }
}
</script>

<style scoped>
@import "../assets/css/Main.css";
</style>