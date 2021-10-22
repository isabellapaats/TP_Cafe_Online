<template>
  <div id="main">
    <div class="main-box">
      <span class="button-box">{{title1}}</span>
      <img src="https://sm.pcmag.com/pcmag_uk/news/p/pre-order-your-coffee-with-square-app/pre-order-your-coffee-with-square-app_6je6.jpg" alt="Img pedir online">
      <p class="phrases">{{p1}}</p>
    </div>
    <div class="main-box">
      <span class="button-box">{{ title2 }}</span>
      <img src="https://buenprovecho.hn/wp-content/uploads/2020/09/Cafe_3.jpg" alt="Img café">
      <p class="phrases">{{p2}}</p>
    </div>
    <div class="main-box">
      <span class="button-box">{{title3}}</span>
      <img src="https://i2.wp.com/thesweetmolcajete.com/wp-content/uploads/2018/09/15-ideas-de-snacks-saludables-Muffins-Saludables-de-Doble-Chocolate.jpg?resize=600%2C900&ssl=1" alt="Img snacks">
      <p class="phrases">{{p3}}</p>
    </div>

  </div>

</template>

<script>
export default {
  name: "Home",
  data (){
    return{
      title1:"Pedidos Online",
      title2:"Menú Café",
      title3: "Menú Snacks",
      p1:" EN SOLO 3 PASOS",
      p2:"¡Un café siempre es una buena idea!",
      p3:"MOMENTOS DULCES"
    }

  }

}
</script>

<style scoped>
@import "../assets/css/Home.css";

</style>