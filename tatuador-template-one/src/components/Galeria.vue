<template>
  <section class="galeria">
    <div id="galeria"></div>
    <div class="container">
      <h2 class="title">Galeria</h2>
      <hr />
      <div class="cards-group">
        <div class="row">
          <div class="card">
            <img src="../assets/img/IMG_4379-scaled.jpg" alt="" />
          </div>
          <div class="card">
            <img src="../assets/img/4-1-700x854.jpg" alt="" />
          </div>
          <div class="card text">
            <p>
              Experiente tatuador, conquistou diversos prêmios em grandes
              eventos nacionais de tatuagem e tatuou no exterior em países como
              Argentina, EUA e Portugal.ver prêmios
            </p>
          </div>
        </div>
        <div class="row">
          <div class="card">
            <img src="../assets/img/2-scaled.jpg" alt="" />
          </div>
          <div class="card">
            <img src="../assets/img/IMG_1469-700x1050.jpg" alt="" />
          </div>
          <div class="card">
            <img src="../assets/img/IMG_8117-700x901.jpg" alt="" />
          </div>
        </div>
        <div class="row">
          <div class="card">
            <img src="../assets/img/STUDIO-1-700x525.jpg" alt="" />
          </div>
          <div class="card text">
            <p>
              Com um studio localizado na região do Brooklin (SP), as sessões
              são realizadas com hora marcada e apenas um cliente por dia para
              proporcionar a melhor experiência de atendimento e exclusividade.
            </p>
          </div>
          <div class="card">
            <img src="../assets/img/STUDIO-2-700x395.jpg" alt="" />
          </div>
        </div>
        <div class="row">
          <div class="card">
            <img src="../assets/img/WORKSHOP-1-700x525.jpg" alt="" />
          </div>
          <div class="card">
            <img src="../assets/img/WORKSHOP-3-700x549.jpeg" alt="" />
          </div>
          <div class="card text">
            <p>
              Fernando Souza também ministra cursos presenciais e online
              transmitindo sua experiência e conhecimento, incentivando o
              crescimento e a profissionalização do mercado de tatuagem no
              Brasil.
            </p>
          </div>
        </div>
      </div>
      <div class="btn">
        <a href="">CONFIRA MAIS</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.title {
  color: #c5c5c5;
  letter-spacing: 5px;
  font-size: 40px;
  font-family: "Playfair Display", serif;
  margin-top: 10px;
  text-transform: lowercase;
}

#galeria {
  min-height: 1px;
}

.container {
  margin-top: 40px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.container hr {
  margin: 10px 0 30px 0;
  min-width: 300px;
}

.cards-group {
  display: flex;
  flex-direction: column;
}

.row {
  width: 100%;
  display: flex;
  flex-direction: row;
  margin: 1vw 0;
}

.card {
  background-color: #444;
  width: 33%;
  max-width: 300px;
  height: 200px;
  overflow: hidden;
  margin: 0 1vw;
}

.card img {
  min-width: 200px;
  width: 100%;
  min-height: 200px;
}

.text {
  display: flex;
  align-items: center;
  justify-content: center;
}

.text p {
  color: #c5c5c5;
  font-family: "Roboto", Helvetica, Arial, sans-serif;
  line-height: 23px;
  margin: 10px 25px;
}

.btn {
  margin: 50px 0;
}

.btn a {
  text-decoration: none;
  padding: 10px 20px;
  color: #ca9e67;
  border-style: solid;
  border-width: 1px;
  border-color: #ca9e67;
  font-weight: 300;
  font-family: "Roboto", Helvetica, Arial, sans-serif;
}
.btn a:hover {
  text-decoration: underline 2px;
  border-width: 2px;
}

@media (max-width: 700px) {
  .text p {
    font-size: 0.875em;
    line-height: 15px;
  }

  .cards-group {
    display: flex;
    flex-direction: column;
    width: 100vw;
  }

  .row {
    flex-direction: column;
  }

  .card {
    min-width: 70%;
    min-height: 300px;
    margin: 15px auto;
}
 .card img{
    min-height: 100%;
}
}
</style>