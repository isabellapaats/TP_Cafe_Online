<template>
<div id="main-container-navbar">
  <p class="menu"> {{A}} </p>
  <p class="menu">{{B}}</p>
  <p class="menu"> {{C}} </p>
  <p class="menu"> {{D}} </p>
  <p class="menu"> {{E}} </p>

</div>
</template>

<script>
export default {
  name: "navBar",
  data(){
    return{
      A:"Home",
      B: "Menú Café",
      C: "Menú Snacks",
      D: "Pedidos Online",
      E: "Contactanos"

    }

  }
}



</script>

<style scoped>
@import "../assets/css/navBar.css";
</style>