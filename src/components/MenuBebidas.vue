<template>
  <div class="menu-main">
    <div class="menu-header">
      <h1 class="menu-title">{{MenuTitle}} </h1>
    </div>

    <div class="products-container">
      <MenuProduct v-for="(product, index) in product" v-bind:key="index"
                   v-bind:name="product.name"
                   v-bind:image="product.image"
                   v-bind:description="product.description"

      />


    </div>
    <div class="menu-footer">
      <h1 class="menu-text-footer">{{textFooter}}</h1>

    </div>


  </div>
</template>

<script>
import MenuProduct from "@/components/MenuProduct";
import {bebidas} from "@/components/products";

export default {
  name: "MenuBebidas",
  components:{MenuProduct},
  data(){
    return{
      MenuTitle:"Menú de Bebidas",
      textFooter: "Conocé nuestro estilo",
      product: bebidas
    }
  }
}
</script>

<style scoped>

</style>