@@ -12,7 +12,7 @@
<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="cenario-passo0.png" alt="">
            <img src="img/cenario-passo0.png" alt="">
            <p>Um dia desses, dentro de um livro da biblioteca da escola, eu descobri uma carta antiga sobre uma cidade perdida, escondida por riquezas e belezas naturais. Nessa carta, a autora deixa algumas pistas para encontrar essa cidade e eu decidi segui-las!</p>
            <button class="btn-proximo" data-proximo="1">Rio de Janeiro</button>
            <button class="btn-proximo" data-proximo="2">Pernambuco</button>
@@ -27,6 +27,63 @@
            <button class="btn-proximo" data-proximo="5">Investigar as igrejas antigas</button>
            <button class="btn-proximo" data-proximo="6">Explorar as praias próximas</button>
        </div>
        <div class="passo" id="passo-3">
            <p>No topo do Pico da Tijuca, você encontra uma antiga inscrição apontando que a próxima pista está
                localizada no Amazonas.</p>
            <button class="btn-proximo" data-proximo="7">Seguir para o Amazonas</button>
        </div>

        <div class="passo" id="passo-4">
            <img src="img/cenario-passo4-voltar-casa.png" alt="imagem voltando para casa e desitindo da aventura">
            <p>Você decide que a aventura é grande demais e volta para casa, mas sempre se pergunta o que teria
                encontrado.</p>
        </div>

        <div class="passo" id="passo-5">
            <p>Nas igrejas de Olinda, você descobre um mapa antigo escondido atrás de um altar, apontando que a próxima
                pista está no Amazonas.</p>
            <button class="btn-proximo" data-proximo="7">Viajar para o Amazonas</button>
        </div>

        <div class="passo" id="passo-6">
            <p>Explorando as praias, você encontra uma caverna escondida, mas ela leva a um beco sem saída.</p>
            <button class="btn-proximo" data-proximo="8">Voltar e explorar as igrejas</button>
        </div>

        <div class="passo" id="passo-7">
            <p>No Amazonas, a busca pela cidade perdida se intensifica. Você se depara com um rio bifurcado.</p>
            <button class="btn-proximo" data-proximo="9">Seguir pelo rio à esquerda</button>
            <button class="btn-proximo" data-proximo="10">Seguir pelo rio à direita</button>
        </div>

        <div class="passo" id="passo-8">
            <p>De volta às igrejas, você finalmente encontra o mapa antigo. Agora, para o Amazonas!</p>
            <button class="btn-proximo" data-proximo="7">Seguir para o Amazonas</button>
        </div>

        <div class="passo" id="passo-9">
            <p>O rio à esquerda leva você a uma cachoeira escondida com inscrições antigas que revelam a entrada da
                cidade perdida.</p>
            <button class="btn-proximo" data-proximo="11">Explorar a cidade perdida</button>
        </div>

        <div class="passo" id="passo-10">
            <p>O rio à direita termina em uma área pantanosa. Apesar de belas vistas, não há sinais da cidade perdida
                aqui.</p>
            <button class="btn-proximo" data-proximo="12">Retornar e tentar o outro rio</button>
        </div>

        <div class="passo" id="passo-11">
            <img src="img/cenario-passo12-cidade-perdida.png" alt="encontrando uma cidade maravilhosa perdida no Amazonas">
            <p>Dentro da cidade perdida, você descobre tesouros inimagináveis e decide se dedicar a estudar e preservar
                este lugar</p>
        </div>

        <div class="passo" id="passo-12">
            <p>Retornando e escolhendo o rio à esquerda, você finalmente encontra a cachoeira escondida e as inscrições
                que levam à cidade perdida.</p>
            <button class="btn-proximo" data-proximo="11">Explorar a cidade perdida</button>
        </div>
    </main>
    <script src="script.js"></script>
</body>
