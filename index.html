<html>

<head>
    <title>
        Imersão Dev - Aula 08
    </title>
</head>

<style>
    body {
        font-family: 'Roboto Mono', monospace;
        min-height: 854px;
        background-image: linear-gradient(to bottom,#08804e,#342e47);
        background-color: #000000;
        background-size: cover;
        background-position: center top;
        background-repeat: no-repeat;
        padding-bottom: 20vh;
    }

    span {
        background-color: #f5ec6ece
    }

    .footer{
        font-family: 'Courier New', Courier, monospace;
        color:#ffffff;
        position: absolute;
        top: 0;
    }

    .container {
        text-align: center;
        padding: 20px;
    }

    .page-title {
        color: #ffffff;
        margin: 5px 0;
    }

    button, .button-jogar {
        padding: .8rem 1.5rem;
        margin: 1rem 0;
        border-radius: 5px;
        border: none;
        font-size: 1rem;
    }

    h2 {
        color: white;
    }

    #carta-jogador, #carta-maquina {
        width: 360px;
        height: 500px;
        overflow: auto;
        border-radius: 10px;
        margin-bottom: 20px;
        margin: 0 auto;
        display: flex;
        align-items: flex-end;
        position: relative;
        background-size: 350px 300px;
        background-repeat: no-repeat;
        background-position-x: 5px;
        background-position-y: 10px;
        border-radius: 33px;
    }

    #carta-jogador h3 {
        text-align: center;
    }

    .carta-imagem {
        border: 1px solid black;
        height: 100px;
        margin: 10px;
    }

    .carta-imagem img {
        width: 100%;
        height: 100%;
    }

    .carta-status {
        height: 160px;
        margin: 2rem;
        color: white;
        z-index: 2;
    }

    .carta-status input {
        margin: 20px 10px;
    }

    .resultado-final {
        color: white;
        font-size: 2rem;
        text-transform: uppercase;
        font-weight: lighter;
        padding: 1rem;
        border: 2px solid black;
        background-color: black;
    }

    .--spacing {
        margin-left: 2.5rem;
    }

    form {
        display: flex;
        flex-direction: column;
    }

    .wrapper {
        display: flex;
        justify-content: space-between;
        width: 100%;
    }

    .carta-subtitle {
        z-index: 2;
        position: absolute;
        top: 16px;
        left: 37px;
        font-weight: 800;
        text-transform: uppercase;
        color:#2a2a3f
    }

    #cartas {
        width: 100%;
        display: flex;
        justify-content: space-between;
    }

    .carta {
        background-color: #2a2a3f;
    }

    .carta-status p {
        margin-bottom: 2rem;
    }

    .opcoes {
        color:#ffffff    
    }

    .--spacing {
        margin-left: 2.5rem;
    }

    .interface {
        color: #ffffff;
        font-family: 'Courier New', Courier, monospace;
    }
</style>

<body>
    <div class="container">
        <h1 class="page-title">Super Trunfo</h1>
        <button onclick="sortearCarta()" id="btnSortear">Sortear carta</button>
        <form id="form">
            <h2>Escolha o seu atributo</h2>
            <div class="wrapper">
                <div id= "cartas">
                    <div id="carta-jogador" class="carta">
                        <img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/card-super-trunfo-transparent-ajustado.png"
                            style=" width: inherit; height: inherit; position: absolute;">
                        <h3></h3>
                    </div>
                    <div id="placar" class= "interface"></div>
                    <div id="carta-maquina" class="carta"><img
                            src="https://www.alura.com.br/assets/img/imersoes/dev-2021/card-super-trunfo-transparent-ajustado.png"
                            style=" width: inherit; height: inherit; position: absolute;">
                    </div>
                </div>
            </div>
            <br>
            <div id="quantidade-cartas" class= "interface"></div>
            <br>
            <button class="button-jogar" type="button" id="btnJogar" onclick="jogar()" disabled="false">Jogar</button>
            <button class= "button" type= "button" id= "btnNovaPartida" disabled="false" onclick= "novaPartida()" disabled ="true" > nova partida</button>
            <div id="resultado"></div>
            <div id="fim"></div>
        </form>
        <br>
        <br>
        <footer class="footer">imersão<span>Dev_</span></footer>
    </div>

</body>

<script>
    let carta1 = {
        nome: "bulbassauro",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/001.png",
        atributos: {
            ataque: 75,
            defesa: 60,
            magia: 90
        }
    }
    let carta2 = {
        nome: "squirtle",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/007.png",
        atributos: {
            ataque: 80,
            defesa: 90,
            magia: 60
        }
    }
    let carta3 = {
        nome: "charmander",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/004.png",
        atributos: {
            ataque: 90,
            defesa: 70,
            magia: 75
        }
    }
    let carta4 = {
        nome: "pikachu",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/025.png",
        atributos: {
            ataque: 65,
            defesa: 70,
            magia: 95
        }
    }  
    let carta5  = {
        nome: "umbreon",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/197.png",
        atributos: {
            ataque: 80,
            defesa: 70,
            magia: 85
        }
    } 
    let carta6  = {
        nome: "lugia",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/249.png",
        atributos: {
            ataque: 80,
            defesa: 85,
            magia: 98
        }
    } 
    let carta7  = {
        nome: "cyndaqil",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/155.png",
        atributos: {
            ataque: 70,
            defesa: 65,
            magia: 85
        }
    } 
    let carta8  = {
        nome: "buizel",
        imagem: "https://assets.pokemon.com/assets/cms2/img/pokedex/detail/418.png",
        atributos: {
            ataque: 80,
            defesa: 80,
            magia: 80
        }
    } 
    

    let cartas = [carta1, carta2, carta3, carta4, carta5, carta6, carta7, carta8]
    let cartaPlayer
    let cartaPC
    let pontosPlayer = 0
    let pontosPC = 0

    atualizaPlacar()
    atualizaDeck()

    function novaPartida(){
        let divCartas = document.getElementById("cartas")
        divCartas.innerHTML = ` <div id="carta-jogador" class="carta">
                        <img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/card-super-trunfo-transparent-ajustado.png"
                            style=" width: inherit; height: inherit; position: absolute;">
                        <h3></h3>
                    </div>
                    <div id="placar" class= "interface"></div>
                    <div id="carta-maquina" class="carta"><img
                            src="https://www.alura.com.br/assets/img/imersoes/dev-2021/card-super-trunfo-transparent-ajustado.png"
                            style=" width: inherit; height: inherit; position: absolute;">
                    </div>`
        atualizaPlacar()
        document.getElementById("btnNovaPartida").disabled=true
        document.getElementById("btnSortear").disabled=false
        
    }
    function atualizaDeck(){
        let deck= document.getElementById("quantidade-cartas")
        let texto= "restam "+ cartas.length + " cartas" 
        deck.innerHTML = texto
    }
    function atualizaPlacar(){
        let placar = document.getElementById("placar")
        let html = `jogador: ${pontosPlayer} / maquina: ${pontosPC}`
        placar.innerHTML = html

    }
    function  sortearCarta(){
        let inimigoClear = document.getElementById("carta-maquina")
        inimigoClear.style.backgroundImage = ""
        let numeroPC
        let numeroPlayer
        inimigoClear.innerHTML = `<img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/card-super-trunfo-transparent-ajustado.png" style=" width: inherit; height: inherit; position: absolute;">`
        numeroPC = parseInt(Math.random() * cartas.length)
        console.log(cartas[numeroPC])
        cartaPC = cartas[numeroPC]
        cartas.splice(numeroPC,1)
        if(cartas.length > 1 ){
            numeroPlayer = parseInt(Math.random() * 3)
        }else{
            numeroPlayer = 0
        }
        cartaPlayer = cartas[numeroPlayer]
        console.log(cartas[numeroPlayer])
        cartas.splice(numeroPlayer,1)
        atualizaDeck()
        document.getElementById("btnSortear").disabled = true
        document.getElementById("btnJogar").disabled = false
        exibirCartas()
        console.log(cartaPC.nome + " " + cartaPlayer.nome)
    }
    function obtemOpcao(){
        let selecionado = document.getElementsByName('atributo')
        for(let i =0; i < selecionado.length; i++){
            if(selecionado[i].checked){
                console.log(selecionado[i])
                return selecionado[i].value
            }
        }
    }
    function exibirCartas(){
        let cartaJogador = document.getElementById("carta-jogador")
        cartaJogador.innerHTML = `<img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/card-super-trunfo-transparent-ajustado.png" style=" width: inherit; height: inherit; position: absolute;"> <h3></h3>`
        cartaJogador.style.backgroundImage = `url("${cartaPlayer.imagem}")`
        let nome =  `<p class = "carta-subtitle" >${cartaPlayer.nome}</p>`
        let html = ""
        for(let atributo in cartaPlayer.atributos){
            html += `<input type= 'radio' name= 'atributo' value= '${atributo}'> ${atributo} + ${cartaPlayer.atributos[atributo]} <br>`
        }
        let ajuste = `<div id="opcoes" class= "carta-status">`
        cartaJogador.innerHTML += nome + ajuste + html + "</div>"
        
    }

    function exibirCartaMaquina(){
        let cartaMaquina = document.getElementById("carta-maquina")
        cartaMaquina.style.backgroundImage= `url('${cartaPC.imagem}')`
        let nome =  `<p class = "carta-subtitle" >${cartaPC.nome}</p>`
        console.log(cartaPC.nome)
        let html = ""
        for(let atributo in cartaPC.atributos){
            html += `<p type= 'texto' name= 'atributo' value= '${atributo}'> ${atributo} + ${cartaPC.atributos[atributo]} <br>`
        }
        let ajuste = `<div id="opcoes" class= "carta-status">`    
        cartaMaquina.innerHTML += nome + ajuste + html + "</div>"
        console.log(cartaMaquina.innerHTML)
    }

    function jogar(){
        let atributoEscolhido = obtemOpcao()
        let resultado = document.getElementById("resultado")
        let resposta = ""
        if(cartaPC.atributos[atributoEscolhido] == cartaPlayer.atributos[atributoEscolhido]){
            resposta = `<p class= "resultado-final"> Empate </P>`
        }else if(cartaPC.atributos[atributoEscolhido] > cartaPlayer.atributos[atributoEscolhido]){
            resposta = `<p class= "resultado-final"> Derrota </P>`
            pontosPC++
        }else if(cartaPC.atributos[atributoEscolhido] < cartaPlayer.atributos[atributoEscolhido]){
            resposta = `<p class= "resultado-final"> Vitoria </P>`
            pontosPlayer++    
        }
        resultado.innerHTML = resposta
        exibirCartaMaquina()
        atualizaPlacar()
        if(cartas.length == 0){
            let botao = document.getElementById("fim")
            let display = document.getElementById("resultado")
            botao.innerHTML = `<button class= "button" type= "button" id= "btnNovaPartida" onclick= "window.location.reload()"> tentar novamente</button>`
            if(pontosPlayer > pontosPC){
                display.innerHTML = `<p class= "resultado-final"> Parabens! Você ganhou do computador</p>`
            }else if(pontosPlayer == pontosPC){
                display.innerHTML = `<p class= "resultado-final"> Nossa! Você empatou com o computador</p>`
            }else{
                display.innerHTML = `<p class= "resultado-final"> Que pena! dessa vez o computador venceu</p>`
            }
            document.getElementById("btnNovaPartida").disabled = true
        }else{
            document.getElementById("btnNovaPartida").disabled = false
            document.getElementById("btnJogar").disabled = true
        } 
    }
</script>

</html>
