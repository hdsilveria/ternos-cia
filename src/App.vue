<template>
<div id="app">

<div class="w3-bar w3-top w3-border" id="menu">
  <div class="w3-right">
      <a class="w3-bar-item w3-button w3-hover-white w3-hover-text-teal" @click="empresa">Empresa</a>
      <a class="w3-bar-item w3-button w3-hover-white w3-hover-text-teal" @click="camisaria">Camisaria</a>
      <a class="w3-bar-item w3-button w3-hover-white w3-hover-text-teal" @click="alfaiateria">Alfaiateria</a>
      <a class="w3-bar-item w3-button w3-hover-white w3-hover-text-teal" @click="depoimentos">Depoimentos</a>
      <a class="w3-bar-item w3-button w3-hover-white w3-hover-text-teal" @click="contato">Contato</a>
    </div>
  </div>

<empresa class="empresa" />
<sobre class="sobre" />
<opiniao class="opiniao" />
<qualidades class="qualidades" />
<condicoes class="condicoes" />
<camisaria  class="camisaria"/>
<depoimentos  class="depoimentos"/>
<contatos  class="contatos"/>


<footer>
  <hr>
   <p>Desenvolvido por &copy;Henrique_Duarte</p><br>
</footer>
    
</div>
</template>

<script>

import empresa from './components/empresa'
import sobre from './components/sobre'
import opiniao from './components/opiniao'
import qualidades from './components/qualidades'
import condicoes from './components/condicoes'
import depoimentos from './components/depoimentos'
import contatos from './components/contatos'
import camisaria from './components/camisaria'
import scrollToElement  from 'scroll-to-element'

export default {
  name: 'App',
  components: {
    empresa,
    sobre,
    opiniao,
    qualidades,
    condicoes,
    depoimentos,
    contatos,
    camisaria
  },

  methods:{

    empresa: function () {
      scrollToElement('.sobre', {
        offset: 0,
        duration: 2500
    })
  },

    camisaria: function () {
      scrollToElement('.camisaria', {
        offset: 0,
        duration: 2500
    })
  },

    alfaiateria: function () {
      scrollToElement('.camisaria', {
        offset: 0,
        duration: 2500
    })
  },

    depoimentos: function () {
      scrollToElement('.depoimentos', {
        offset: 0,
        duration: 2500
    })
  },

    contato: function () {
      scrollToElement('.contatos', {
        offset: 0,
        duration: 2500
    })
  },

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#menu {
  padding: 1%;
  background-color: rgba(255, 255, 255, 0.979);
  color: #8a8a8a;
  font-size: 14pt;
}

@media screen and (max-width: 650px) {
#app {
    width: 650px;
}
}

</style>
