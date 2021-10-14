<template>
  <div id="empresaPrincip">
    
    
<div>
  <img src="../assets/img_1_topo.png">
<b-row>
  <b-col>
    <div class="w3-display-left" id="slogan">
      <div>
        <p><i>Elegante é ter um</i><br>
        <b>Alfaiate</b>
        <br><i>para chamar de seu.</i></p>
      </div>
    </div>

    <div class="w3-display-bottomleft" style="color: white; text-align: left;margin: 30px; font-size: 14pt; ">
        <p>compre hoje, pague em até 3x <br>com 12% de desconto e tenha <br>10 meses para confeccionar.</p>
        <button class="w3-button w3-round-large">Faça ja um orçamento</button>
    </div>
  </b-col>
</b-row>

</div>
  </div>
</template>

<script>
export default {
  name: 'empresa'
}
</script>

<style scoped>


#slogan {
  font-family: Gabriola;
  font-size: 32pt;
  margin: 20px;
  text-align: center;
  color: white;
}

b {
  color: rgb(26, 107, 145); 
  font-family: Felix Titling; 
  font-size: 40pt;
  margin-left: 50px;
}

button {
  background-color: rgb(103, 134, 190);
  color: white;
}

i {
  color: rgb(233, 175, 127)
}

@media screen and (min-width: 992px) {
img {
  width: 100%;
  height: 625px; 
}
}

@media screen and (max-width: 650px) {
img {
  width: 121vh !important;
  height: 100vh; 
}
#empresaPrincip {
  width: auto !important;
}
}

</style>
