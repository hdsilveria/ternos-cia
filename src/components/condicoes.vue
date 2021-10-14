<template>
<div id="prinCondicoes">

<b-row>
    <b-col>

        <h3>Condição imperdível</h3><br><br>

        <h4>Compre hoje e garanta:</h4><br><br>
        <p>- 12% de desconto e pagamento em até <b>3x sem jutos;</b></p><br>
        <p>- Até <b>10 meses</b> para confeccionar sua roupa. Não se preocupe se suas medidas aumentaram ou diminuiram, estará sempre elegante;</p><br>
        <p>- Condição muito especial por <b>tempo limitado;</b></p><br>
        <p>- Poder presentear alguém com uma roupa de alta costura, <b>exclusiva;</b></p><br><br>

        <button class="w3-button w3-round-large" style="">Garanta essa condição especial !</button>
        
    </b-col>

    <b-col>
        <img src="../assets/img_condicoes.png">        
    </b-col>
</b-row>

</div>
</template>

<script>
export default {
    name: 'condicoes'
}
</script>

<style scoped>

@media screen and (max-width: 650px) {
#prinCondicoes {
    width: 650px;
}
}

div#prinCondicoes {
    background-color: rgba(0, 65, 85, 0.897);
    color: white;
    padding: 5%;
}

h3 {
    font-family: Felix Titling;
    font-size: 26pt;
    color: rgb(233, 175, 127);
}

h4 {

    font-family: Felix Titling;
    font-size: 18pt;
    color: rgb(233, 175, 127);

}

p {
    text-align: left;
    font-size: 13pt;
}

button {
    background-color: rgb(233, 175, 127); 
    color: white;
    font-size: 14pt;
}

</style>