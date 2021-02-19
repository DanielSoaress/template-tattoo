<template>
  <section class="about">
    <div id="sobre"></div>
    <div class="container">
      <div class="about-img">
        <img src="../assets/img/fernando_souza.jpg" alt="Fernando Souza" />
      </div>
      <div class="conteudo">
        <h2 class="title">sobre</h2>
        <hr />
        <div class="text">
          <p>
            Desde criança já passava grande parte do tempo observando e criando
            desenhos, estudou em diversas escolas de arte, buscando a excelência
            no que praticava.
          </p>
          <p>
            Em 2007 teve seu primeiro contato com a tatuagem como profissão e
            desde então vem se especializando através de cursos e workshops com
            os mais renomados artistas do mercado mundial.
          </p>
          <p>
            Sua meta é oferecer um trabalho artístico surpreendente para cada
            cliente e executar cada tatuagem com o máximo de detalhes, volume e
            cores, alcançando o melhor do REALISMO que é hoje sua marca
            registrada no mercado da tatuagem no Brasil.
          </p>
        </div>
      </div>
    </div>
    <div class="cursos">
      <img src="../assets/img/banner_sobre.jpg" alt="Cursos" />
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.about {
  min-height: 92vh;
}

.about-img img {
  display: block;
}

#sobre {
  min-height: 1px;
}

.container {
  margin-top: 40px;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.conteudo {
  color: #c5c5c5;
  text-align: center;
  padding: 0 75px;
  background-color: #1c1d1d;
  width: 100%;
  min-height: 430px;
}

.text {
  font-size: 0.875em;
  font-weight: 300;
  line-height: 16px;
  color: #c5c5c5;
  font-weight: 300;
  font-family: "Roboto", Helvetica, Arial, sans-serif;
}

.title {
  letter-spacing: 3px;
  font-size: 40px;
  font-family: "Playfair Display", serif;
  margin-top: 30px;
}

.text p {
  margin-bottom: 10px;
}

.conteudo hr {
  width: 100%;
  margin: 20px 0;
}

.about .cursos {
  padding: 50px 0 30px 0;
}



@media (max-width: 700px) {
  .container {
    flex-direction: column;
  }

  .conteudo {
      max-width: 290px;
  }

  img {
    width: 100vw;
}
  
}
</style>