<template>
  <div id="app">
    <Nav />

    
    <InHome />

    <Services />

    <Contact />
    

    <Foot />


  </div>
</template>



<script>
import Nav from "./views/Nav";
import InHome from "./views/InHome"
import Services from "./views/Services"
import Contact from "./views/Contact"
import Foot from "./views/Foot"

export default {
  name: 'App',
  components: {
    Nav,
    InHome,
    Services,
    Contact,
    Foot
  }
}
</script>



<style lang="scss">
  $primary: #1a5fc7;
  $secondary: #dbcb1a;
  $enable-gradients: true;
  @import "../node_modules/bootstrap/scss/bootstrap.scss";



  html{
    scroll-behavior: smooth;
  }

  body{
    background-color: #fcfcfc;
  }

  .strong-1 {
    color: #1a5fc7;
  }

  .strong-2{
    color: #dbcb1a;
  }
</style>
