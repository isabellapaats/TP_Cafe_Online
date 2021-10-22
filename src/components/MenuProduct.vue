<template>
  <div id="main-menuProducts">
    <h2 class="product-title"> {{name}}</h2>
    <img   calss="product-image " src="">
    
    
  </div>

</template>

<script>
export default {
  name: "MenuProduct",
  props:[
    "name",
    "image",
    "description"
  ],
  data() {
    return {

    }
  }
}
</script>

<style scoped>
#main-menuProducts{
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
}

</style>