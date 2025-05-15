# heroi

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../index.css">
    <title>Document</title>
</head>
<body>
    <header>
        <h1>Jornada do Héroi</h1>
    </header>
    <main><h2>Introdução</h2>
    <p>Você vai tomar a descisão do heroi, e cada caminho tera suas consequências, seja cuidadoso.</p>
<hr>
<br>
<div class="caminhos">
<button><a href="Caminho1.html">Caminho 1</a></button>
</div>
</main>
</body>
</html>




----------------------------------------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caminho 1</title>
    <link rel="stylesheet" href="../index.css">
</head>
<body>
    <header><h1>Primeira rota...</h1></header>
    <main>
        <h2>Pela manhã</h2>
        <br>
        <p>
            <span style="color: rgb(0, 0, 0);">Oh tal nobre guerreiro, Hoje logo quando os passaros cantarolavam, uma carta é entregue por baixo de sua porta, você... zonzo pela manha, ao percebela logo se aproxima e lê, se trata de um pedido direto de seu Rei... </span><br>
            <br>
            <span style="color: gold;"> "bla bla bla bla, e recupere o meu calice, roubado por Ladrões" </span> <p>Você não se recorda muito, mas pega sua espada e parte em um caminho que você crê que é o correto...</p>
         </p>
         
         <hr>
        <div class="Escolhas">
            <input type="radio" id="escolha1" name="grupo1" value="500" onclick="adicionarPontos(500);verificarRespostas();">
            <label for="escolha1">Seguir reto</label>
            <input type="radio" id="escolha2" name="grupo1" value="0" onclick="adicionarPontos(0);verificarRespostas();">
            <label for="escolha2">Ir para a vila</label>
            <input type="radio" id="escolha3" name="grupo1" value="1000" onclick="adicionarPontos(1000);verificarRespostas();">
            <label for="escolha3">Seguir pela floresta</label>
        </div>
        <hr>
        <span style="color: black;">Você segue seu rumo... em algumas horas caminhando, encontra um pequeno vilarejo em chamas!</span>
      <div class="Escolhas2">
            <input type="radio" id="escolha4" name="grupo2" value="500" onclick="adicionarPontos(500);verificarRespostas();">
            <label for="escolha4">Ignora o evento</label>
            <input type="radio" id="escolha5" name="grupo2" value="0" onclick="adicionarPontos(20);verificarRespostas();">
            <label for="escolha5">Ir ajudar os locais</label>
            <input type="radio" id="escolha6" name="grupo2" value="1000" onclick="adicionarPontos(400);verificarRespostas();">
            <label for="escolha6">Saquear a vila</label>
      </div>
      <br>
      <hr>
     <span style="color: black;">Enfim, após os eventos, você procura um local para descansar, e ao acordar, se encontra em um lugar totalmente novo e desconhecido... uma caverna escura com uma atmosfera tenebrosa...

            Você caminha pelo local por um tempo, um clima frio sempre presente, o local é Umido, mal iluminado e as paredes parecem que já foram submersas diversas vezes,

            Andando mais pelo local, você encontra uma jovem no chão, ela parecia que estava andando a mesma direção, mas algo está errado, ela é palida, paralizada e não emanava sons, talvez seja um cadaver, ou não... Tal anel brilha na mão dela...
     </span>
      <div class="Escolhas3">
            <input type="radio" id="escolha7" name="grupo3" value="500" onclick="adicionarPontos(500);verificarRespostas();">
            <label for="escolha7">Você pega o anel brilhante</label>
            <input type="radio" id="escolha8" name="grupo3" value="0" onclick="adicionarPontos(2500);verificarRespostas();">
            <label for="escolha8">você ignora ela</label>
            <input type="radio" id="escolha9" name="grupo3" value="1000" onclick="adicionarPontos(1000);verificarRespostas();">
            <label for="escolha9">você tenta conversar com ela</label>
            <hr>
    </main>
    <script src="jogo.js"></script>
</body>
</html>

---------------------------------------------------------------


Projeto com
(Variáveis 
Operadores
laços de repetoção
Estrutura de descisões)

Se o XP for menor que 1000=ferro , 10000+ radiante.

No final exibir Nome do heroi mais o nivel dele
