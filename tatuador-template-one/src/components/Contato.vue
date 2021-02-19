<template>
  <section id="contato">
    <div class="container">
      <div class="row">
        <div class="title">
          <h2>contato</h2>
          <hr />
        </div>
      </div>
      <div class="row group-2">
        <div class="col">
          <div class="card">
            <p class="align">
              <img
                src="../assets/img/maps-and-flags.png"
                alt="Instagram"
                width="20"
                height="20"
              />Brooklin, São Paulo - SP
            </p>
            <br />
            <p>Fale conosco direto pelo <br />Whatsapp: (11) 99655-0605</p>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <p>
              Confira também, trabalhos, depoimentos e dicas no <br />Instagram
            </p>
            <br />
            <a href="#" class="align"
              ><img
                src="../assets/img/instagram.png"
                alt="Instagram"
                width="20"
                height="20"
              />
              fernandosouzatattoo</a
            >
          </div>
        </div>
      </div>
    </div>
    <div>
      © Fernando Souza Tattoo - Todos os direitos reservados | Daniel Soares
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.title h2 {
  color: #c5c5c5;
  letter-spacing: 5px;
  font-size: 2.25em;
  font-family: "Playfair Display", serif;
  font-weight: 40;
  text-transform: lowercase;
  margin-bottom: 20px;
  margin-top: 160px;
}

.title hr {
  max-width: 35%;
  margin: 0 auto 40px auto;
}

.row {
  margin-top: 80px;
  margin-left: auto;
  margin-right: auto;
  width: calc(100% - 20px);
}

.col {
  width: calc(33.332% - 20px);
}
.card {
  color: #c5c5c5;
  font-family: "Playfair Display", serif;
  letter-spacing: 2px;
  text-align: justify;
  font-size: 0.875em;
}

.group-2 {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-bottom: 160px;
}

.align {
  display: flex;
  align-items: center;
}

.align img {
  margin-right: 7px;
}

a {
  text-decoration: none;
  color: #c5c5c5;
}

@media (max-width: 700px) {
  #contato {
    width: 100vw;
  }

  .group-2 {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    margin-bottom: 160px;
  }
  .col {
    width: calc(100% - 20px);
  }

  .align {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 10px;
    margin-bottom: 10px;
  }
  .card p {
      padding: 0px 10vw;
      margin-top: 10px;
      margin-bottom: 10px;
  }

  br {
      display: none;
  }
}
</style>