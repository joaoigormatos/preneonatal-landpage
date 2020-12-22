<template>
  <v-app>


    <v-main>
      <AppBar />
        <Hero />
        <Funcionalidades />
        <Depoimentos />
        <Planos />
        <Footer />
    </v-main>
  </v-app>
</template>

<script>
import AppBar from './components/AppBar'
import Hero from './components/Hero'
import Funcionalidades from './components/Funcionalidades'
import Depoimentos from './components/Depoimentos'
import Planos from './components/Planos'
import Footer from './components/Footer'

export default {
  name: 'App',

  components: {
    AppBar,
    Hero,
    Funcionalidades,
    Depoimentos,
    Planos,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>
<style >
    html{font-family: 'Rochester', cursive;}
    h1{
      font-family: 'Rochester';
    }
</style>