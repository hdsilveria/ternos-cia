<template>
<div id="app">

<b-row id="menu" class="w-100" align-h="end">
  <b-col cols="auto" align-self="center">
    <ul class="mt-1 d-flex">
      <li>
        <a @click="empresa">Empresa</a>
      </li>

      <li>
        <a @click="camisaria">Camisaria</a>
      </li>

      <li>
        <a @click="alfaiateria">Alfaiateria</a>
      </li>

      <li>
        <a @click="depoimentos">Depoimentos</a>
      </li>

      <li>
        <a @click="contato">Contato</a>
      </li>
    </ul>
  </b-col>
</b-row>

<div class="content-page">
  <empresa class="empresa" />
  <sobre class="sobre" />
  <opiniao class="opiniao" />
  <qualidades class="qualidades" />
  <condicoes class="condicoes" />
  <camisaria  class="camisaria"/>
  <depoimentos  class="depoimentos"/>
  <contatos  class="contatos"/>
</div>


<footer>
  <hr>
   <p>Desenvolvido por &copy;Henrique_Duarte</p><br>
</footer>
    
</div>
</template>

<script>

window.addEventListener("scroll", () => {
  let header = document.getElementById("menu")
  header.classList.toggle("sticky", window.scrollY > 150)
})

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

  methods: {
    empresa(){
      scrollToElement('.sobre', {
        offset: 0,
        duration: 2500
    })
  },

    camisaria(){
      scrollToElement('.camisaria', {
        offset: 0,
        duration: 2500
    })
  },

    alfaiateria(){
      scrollToElement('.camisaria', {
        offset: 0,
        duration: 2500
    })
  },

    depoimentos(){
      scrollToElement('.depoimentos', {
        offset: 0,
        duration: 2500
    })
  },

    contato(){
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
}

#menu {
  padding: 1%;
  color: #ffffff;
  font-size: 14pt;
  position: fixed;
  transition: 1s;
  top: 0;
  left: 0;
  width: 101% !important;
  z-index: 99;
}

.sticky {
  background-color: rgb(255, 255, 255) !important;
  color: #1d1d1d9f !important;
  box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.199);
}

#menu ul li {
  list-style: none;
}

#menu ul li a {
  margin: 0 15px;
  cursor: pointer;
}


@media screen and (max-width: 650px) {
#app {
    width: 650px;
}
}

</style>
