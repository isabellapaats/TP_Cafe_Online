<template>
  <div>

    <!-- <Header></Header> -->
    <Main></Main>
    <div id="contenedores">
      <navBar></navBar>
      <Home ></Home>
      <Banner></Banner>
    </div>
    <MenuBebidas></MenuBebidas>
    <Footer></Footer>
    <!--<router-view></router-view> -->

  </div>

<router-view></router-view>
</template>

<script>
import Main from "@/components/Main";
//import Header from "@/components/Header";
import Footer from "@/components/Footer";
import Banner from "@/components/Banner";
import Home from "@/components/Home";
import navBar from "@/components/navBar";
import MenuBebidas from "@/components/MenuBebidas";

export default {
  name: 'App',
  components: {
   //Header,
    Main,
    Footer,
    Banner,
    Home,
    navBar,
    MenuBebidas

  }

}
</script>

<style>
#contenedores {
  display:inline-flex;
  flex-direction: row;
  justify-content: space-between;
}

</style>
