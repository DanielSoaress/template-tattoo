<template>
  <section class="depoimentos">
      <div id="depoimentos"></div>
      <div class="container">
          <div class="row group-2">
              <div class="col-5">
                  <div class="card title">
                    <h2>depoimentos</h2>
                    <hr>
                  </div>
                    <div class="card">
                      <p>O atendimento do Fernando é super humanizado, muito diferente do que já enontrei por onde andei. 
                          Fica claro que ele simplesmente ama o que faz e demonstra isso ao executar seu trabalho com perfeição. 
                          Se preocupando com a tolerância de dor do seu cliente, o conforto e o minimalismo da arte. 
                          Definitivamente Fernando Souza é a primeira opção quando perguntam para mim com que tatuar. 
                          Costumo dizer que ele é uma "anomalia" no melhor sentido que pode existir da palavra e,
                           na minha humilde visão, é referência de realismo no Brasil.</p>
                      <hr>
                      <div class="card-footer">
                          RANDYCLEY, CLIENTE DE SALVADOR / BA
                      </div>
                    </div>
              </div>
              <div class="col-5">
                <div class="card ">
                    <p>Esse workshop foi o melhor que fiz, parabéns pela humildade, Fernando, e pelo excelente profissional que você é.
                       Tanto tatuando quanto sendo professor. Me tirou muitas dúvidas com muita precisão nas palavras.
                       Muito obrigado, forte abraço</p>
                    <hr>
                    <div class="card-footer">
                        RODRIGO - TATUADOR - ALUNO DO WORKSHOP DE SÃO PAULO / SP
                    </div>
                </div>
                <div class="card background-dark">
                    <p>Quando se tratava de tatuagem, sempre quis o estilo realista, mas nunca tinha encontrado nenhum 
                        artista que me chamasse a atenção. Conheci o trabalho do Fernando há uns dois anos. 
                        Mostrava para todos que conhecia e dizia que, se um dia fizesse alguma, seria com ele. 
                        Hoje realizei essa vontade. O trampo? Não preciso dizer que superou minhas expectativas. 
                        Além de tudo, o cara é sensacional, humilde e te deixa muito a vontade.</p>
                    <hr>
                    <div class="card-footer">
                        YGOR - CLIENTE DE SÃO PAULO / SP
                    </div>
                </div>
              </div>
          </div>
          <div class="row">
              <div class="card">
                    <p>Sem dúvidas o melhor workshop presencial que já fiz. O cuidado em passar dicas, desde a escolha da imagem,
                         papel certo para impressão, número de gotas no batoque, tudo muito bem explicado e dinâmico. 
                         Foi uma evolução enorme nos meus trabalhos, tanto que até meus clientes comentaram.</p>
                    <hr>
                    <div class="card-footer">
                       RAFAEL - TATUADOR - ALUNO DO WORKSHOP PRESENCIAL
                    </div>
                </div>
                <div class="card background-dark">
                    <p>Eu estava à procura de um profissional especialista em Tatuagens realistas e comecei a busca pela internet 
                        através do Google e das redes sociais até que comecei a ler alguns comentários muito positivos sobre um 
                        cara chamado FERNANDO SOUZA. Então comecei a pesquisar sobre seu trabalho, analisar seu portfólio e aí 
                        tive a certeza que você seria o profissional que conseguiria atender minhas expectativas com a perfeição 
                        que eu queria. Mesmo sendo em uma cidade distante da minha eu não me importei, tamanha foi minha admiração por 
                        seu trabalho. Ao chegar até seu estúdio fui muito bem recebido e o mais importante, “fui ouvido”, ele se mostrou 
                        interessado em realmente entender qual a importância do desenho e como eu gostaria que fosse, isso me passou 
                        tranquilidade e confiança. Após a primeira sessão eu fiquei feliz por saber que havia feito a escolha certa pois a 
                        arte ficou perfeita. Após a segunda sessão fiquei mais feliz ainda pois ficou exatamente como eu gostaria. 
                        Com certeza será você o tatuador das minhas próximas tatuagens.</p>
                    <hr>
                    <div class="card-footer">
                        GABRIEL FERRAZ, 34 ANOS EMPRESÁRIO - BELO HORIZONTE/MG
                    </div>
                </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
#depoimentos {
    min-height: 1px;
}

.container {
    margin-top: 60px;
}

.card p {
    color: #c5c5c5;
    margin-bottom: 15px;
}

.card.title hr {
    border-color: #c5c5c5;
}

.card hr {
    border-color: #ca9e67;
}

.title h2{
    color: #c5c5c5;
    letter-spacing: 5px;
    font-size: 2em;
    font-family: 'Playfair Display', serif;
    font-weight: 400;
    text-transform: lowercase;
    margin-bottom: 10px;
}

.title hr {
    width: 80%;
    margin: 0 auto;
}

.title {
    background-color: rgba(34, 34, 34, 0.658);
    text-align: center;
}

.card {
    padding: 20px 20px;
    text-align: center;
    font-family: 'Roboto', Helvetica, Arial, sans-serif;
    letter-spacing: 2px;
    font-size: 0.875em;
    font-weight: 300;
    margin-bottom: 20px;
}

.card .card-footer{
   padding: 20px 10px 0 20px;
   font-size: 1.125em;
   color: #ca9e67;
}

.background-dark{
    background-color: rgba(34, 34, 34, 0.658);
}

.group-2 {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}

.col {
    width: calc(100% - 20px)
}

.row {
    margin-right: auto;
    margin-left: auto;
    width: calc(100% - 20px)
}

.col-4 {
    width: calc(33.333% - 20px);
}
.col-5 {
    width: calc(41.665% - 20px);
}

.col-7 {
    width: calc(58.331% - 20px);
}
.col-8 {
    width: calc(66.664% - 20px);
}

@media (max-width: 700px) {
 .group-2 {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

.col-5, .col-4, .col-6, .col-7, .col-8 {
    width: 100%;
}
}

</style>