<template>
  <Navbar /> <!-- Navbar padrão para todas as páginas -->

  <router-view/><!-- Onde vai ficar o conteúdo da página -->
  
  <Footer />
</template>

<script>
// Importando componentes externos
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>

<style>
template {
  width: 100vw;
  height: auto;
}


-webkit-scrollbar-track { background-color: #ffffff; } ::-webkit-scrollbar { width: 6px; background: #6184bb; } 

::-webkit-scrollbar-thumb { background: #1B3764; }

-webkit-scrollbar-track { background-color: #ffffff; } ::-webkit-scrollbar { width: 6px; background: #6184bb; } 

::-webkit-scrollbar-thumb { background: #1B3764; }
</style>