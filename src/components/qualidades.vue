<template>
<div id="prinQualidades">

    <div class="w3-row">

    <div class="w3-col s4 w3-white w3-center">
        <img src="../assets/qualidade.png">
        <h3>Qualidade</h3>
        <small>Camisaria e Alfaiateria 100% artesanal.</small>
    </div>

    <div class="w3-col s4 w3-center">
        <img src="../assets/confianca.png">
        <h3>Confiança</h3>
        <small>Atendimento personalizado no escritorio ou residencia.</small>
    </div>

    <div class="w3-col s4 w3-white w3-center">
        <img src="../assets/experiencia.png">
      <h3>Experiencia</h3>
      <small>Tradição e modernidade proporcionando elegancia.</small>
    </div>
</div>

</div>
</template>

<script>
export default {
    name: 'qualidades'
}
</script>

<style scoped>

@media screen and (max-width: 650px) {
#prinQualidades {
width: 650px;
}
}

div#prinQualidades {
    padding: 3%;
}

h3 {
    color: rgb(65, 100, 163);
    font-family: Felix Titling;
}

small {
    color: rgb(107, 107, 107);
}

img {
    width: 15%;
    margin: 15px;
}

</style>