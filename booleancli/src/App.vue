<template>
  <div id="app">
    <Header />
    <PageMain />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import PageMain from "./components/PageMain.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {
    Header,
    PageMain,
    Footer,
  }
}
</script>

<style lang="scss">
@import "style/variables";
@import "style/headerStyle";
@import "style/pageMainStyle";
@import "style/footerStyle.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


*{
   margin: 0;  
   padding: 0;  
   box-sizing: border-box;
}
</style>
