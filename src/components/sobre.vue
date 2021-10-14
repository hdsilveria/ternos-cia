<template>
<div id="PrinSobre">
    <br><br>

<b-row class="mt-5" align-h="center">
    <b-col md="5">
    <h3>Ternos & CIA</h3><br>

      <p>Com mais de 35 anos de experiencia em camisas, calças e ternos sob medida, possuimos profissionais experientes e altamente qualificados.</p>

      <p>Cada cliente tem seu molde exclusivamente desenvolvida para seu biotipo através das medidas tiradas pelo próprio, no escritório ou residencia do cliente.</p>
      
      <br>

      <p><i>"Nosso objetivo é superar a expectativa do cliente proporcionando-lhe satisfação ao usar nossos produtos, aliado a um relacionamento franco e honesto, valorizando o ser humano."</i></p>

      <button class="w3-button w3-round-large" style="background-color: rgb(103, 134, 190); color: white">Agende uma visita</button>
    </b-col>

    <b-col md="auto" class="w3-white w3-center">
      <img src="../assets/perfil_sobre.jpg" alt="ternosEcia">
    </b-col>
</b-row>


</div>
</template>

<script>
export default {
    name: 'sobre'
}
</script>

<style scoped>

@media screen and (max-width: 650px) {
#PrinSobre {
    width: 600px;
}
}

h3 {
    color: rgb(103, 134, 190);
    text-align: center;
    font-family: Felix Titling;
}

p {
    text-align: left;
}

i {
    color: rgb(103, 134, 190);
}


</style>