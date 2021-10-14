<template>
<div id="PrinDepoimentos">

<b-row>

    <b-col>
      <img src="../assets/depoimento_1.jpg">
    </b-col>

    <b-col>
    <br><br>
    <p>"Faço roupas com Ele há mais de duas décadas, o serviço é impecavel em todos os detalhes, desde a costura ao caimento. Ele tem uma equipe de mestre!".</p>
    
    <div id="comentario">
      <p><i>- Henrique Duarte </i></p>
      <small>Advogado | HD Advogados Associados</small>
    </div>
        
    </b-col>
</b-row>

</div>
</template>

<script scoped>
export default {
    name: 'opiniao'
}
</script>

<style scoped>

div#PrinDepoimentos {
    background-image: url('../assets/depoimento_background.jpg');
    background-repeat: no-repeat;
    padding: 5%;
}


@media screen and (max-width: 650px) {
#PrinDepoimentos {
width: 650px;
}
}

#comentario {
    color: rgb(59, 59, 59)
}

h3 {
    color: rgb(65, 100, 163);
    text-align: left;
}

p {
    text-align: left;
    font-size: 13pt;
}

</style>