<template>
<div id="prinContatos">

    <h3>Contato</h3>

<div class="w3-row container" >
    <div class="w3-col s5 w3-center">
        <div style="margin-top: 40px; text-align: left; margin-left: 10px;">
            <h5>Telefones</h5>
            <p>+55 (11) 3333-3737</p>
            <br>
            <h5>E-mail</h5>
            <p>ternos@ternosecia.com.br</p><br>
        </div>
            <h5>Atendimento personalizado</h5><br>
            <button class="w3-button w3-block w3-border w3-border-blue w3-hover-blue" style="width:70%; margin-left: 30px;">Clique aqui!</button><br><br>
    </div>

    <div class="w3-col s7 w3-center">
        <div style="margin-top: 40px;">

            <div style="text-align:left;" class="form-group col-md-9 container"> 

            <div class="col-auto">
                <input type="text" id="nome_" name="nome" class="form-control" placeholder="Nome"><br>
            </div>

            <div class="col-auto">
                <input type="email" class="form-control" placeholder="E-mail"><br>
            </div>

            <div class="col-auto">
                <textarea class="form-control" rows="3" placeholder="Digite sua mensagem"></textarea><br>
            </div>

            <button class="w3-button w3-block w3-border w3-border-blue w3-hover-blue">Enviar Mensagem</button>
            </div>
        
        </div>
    </div>
</div>

</div>
</template>

<script>
export default {
    name: 'contatos'
}
</script>

<style scoped>

div#prinContatos{
    padding: 3%;
}

h3 {
    color: rgb(65, 100, 163);
    font-family: Felix Titling;
    margin: 30px;
}

h5 {
    font-size: 13pt;
    color: rgb(65, 100, 163);
    font-family: Felix Titling;
}

p {
    font-size: 10pt;
    color: rgb(119, 119, 119);
}

button {
    color: rgb(108, 141, 231);
}

label {
    color: rgb(119, 119, 119)
}



</style>