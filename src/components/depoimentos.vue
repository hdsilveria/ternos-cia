<template>
<div id="princiDepoimentos">


    <h2>Depoimentos</h2>

<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">

<div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
</div>

  <div class="carousel-inner">

    <div class="carousel-item active">
        <div class="row" style="padding: 8%;">
            <div class="col-lg-7">
                <img src="../assets/foto_perfil_depoimento_1.png" style="max-width: 200px;">
            </div>

            <div class="col-lg-5">
                <p>"Tenho a honra de afirmar que enquanto nossas vidas perdurarem o meu conceito é sempre melhor em relação ao, sua pessoa, ao profissional competente e idôneo, sempre pontual, atencioso e preocupado ao atender da melhor maneira os anseios de seus clientes, incluindo este signatário."</p>  
                <small>- José Marques </small><br><br>           
            </div>
      </div>
    </div>

    <div class="carousel-item" data-bs-interval="5000">
         <div class="row" style="padding: 8%;">
            <div class="col-lg-7">
                <img src="../assets/foto_perfil_depoimento_4.png" style="max-width: 200px;">
            </div>

            <div class="col-lg-5">
                <p>"Seu corte tanto de camisas, bem como de ternos são impecaveis, muitos dos meus amigos tem elogiado a vestimenta. Recomendo para quem gosta de perfeição, estamos nos servindo do trabalho do há mais de vinte anos"</p>  
                <small>- Henrique Duarte </small><br><br>           
            </div>
      </div>
    </div>
    
    <div class="carousel-item">
         <div class="row" style="padding: 8%;">
            <div class="col-lg-7">
                <img src="../assets/foto_perfil_depoimento_3.png" style="width: 200px;">
            </div>

            <div class="col-lg-5">
                <p>"Sou cliente dele há uns 12 anos. Nosso primeiro contrato foi por intermédio de meu pai, que já tem uma história de decadas com ele, o excelente atendimento antes e pós venda e a alta qualidade dos materiais usados colocam o produto em outro patamar do ramo."</p>  
                <small>- Luis Carlos </small><br><br>           
            </div>
      </div>
    </div>

  </div>

  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>
</template>

<script>
export default {
    name: 'depoimentos'
}
</script>

<style scoped>

@media screen and (max-width: 650px) {
#princiDepoimentos {
    width: 650px;
}
}

div#princiDepoimentos{
    background-image: url('../assets/depoimentos_bar.jpg');
    background-repeat: no-repeat;
    padding: 6%;
}

p {
    color: white;
    text-align: left;
    margin-left: -30px;
}

small {
    color: rgb(233, 175, 127) ;
}

h2 {
    color: rgb(233, 175, 127);
    font-family: Felix Titling;
    margin: 10px;
}


</style>>
6