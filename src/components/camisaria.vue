<template>
<div id="prinCamisaria" class="container">

<div class="card mb-3">
  <div class="row g-0">
    <div class="col-md-4">
        <div class="zoom">
            <img src="../assets/camisaria_1.png" class="w3-hover-opacity" style="margin: 60px;">
        </div>
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h3 class="card-title">Camisaria <br>
        <small> Confeccionadas artesanalmente </small></h3>
                <div class="w3-row">
                    <div class="w3-col s6 w3-center">
                        <ul>
                            <li>100% Algodão</li>
                            <li>Monograma</li>
                            <li>Slim</li>
                        </ul>
                    </div>

                    <div class="w3-col s6 w3-center">
                         <ul>
                            <li>Nacionais e importadas</li>
                            <li>Tradicionais e esportivas</li>
                            <li>Casamentos</li>
                        </ul>
                    </div>
                </div>
            <br>
              <button class="w3-button w3-round-large" style="background-color: rgb(103, 134, 190); color: white">Quero um orçamento</button>
      </div>
    </div>
  </div>
</div>

<h3 class="card-title">Alfaiataria <br>
    <small> Totalmente feito a mão sob medida </small></h3><br><br>
        <b-row>
            <b-col>
                <ul class="text-nowrap">
                    <li>Fio Super 120 e 130</li>
                    <li>Lã fria Australiana</li>
                    <li>Botões Importados</li>
                </ul>
                <br>
                    <button class="w3-button w3-round-large" style="background-color: rgb(103, 134, 190); color: white">Quero um orçamento</button>
            </b-col>

            <b-col>
                <ul class="text-nowrap">
                    <li>Ternos e Calças</li>
                    <li>Paletós e Smokings</li>
                    <li>Sociais e Esportivos</li>
                </ul>
            </b-col>

            <b-col md="4" id="img-cont">
                <img src="../assets/alfaiataria_1.png" class="w3-hover-opacity mt-3" style="margin-top: -70px;">
            </b-col>

        </b-row>
      
</div>
</template>

<script>

export default {
    name: "camisaria"

}
</script>

<style scoped>


#prinCamisaria {
    padding: 5%;
}

h3 {
    color: rgb(65, 100, 163);
    font-family: Felix Titling;
    margin: 30px;
    font-size: 32pt;
}

small {
    color: rgb(163, 163, 163);
    font-size: 10pt;
}

ul {
    text-align: left;
    list-style-type: square;
    margin: 10px;
}

img {
    width: 90%;
    overflow: hidden;
    border: 2px solid rgb(211, 211, 211);
}

.zoom:hover {
    transition: transform .4s;
    transform: scale(1.3);
}

</style>