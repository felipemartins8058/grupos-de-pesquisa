<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <h1 class="fw-bold mb-4">Grupos de Pesquisa</h1>
      </div>
    </div>

    <div class="row mb-3">
      <div class="col-sm">
        <button class="btn btn-primary px-3 py-3">
          <div class="d-flex justify-content-center align-items-center">
            <div class="text-start">
              <p class="fw-bold mb-1">Buscar Grupos de Pesquisa</p>
              <p>
                Faz parte de algum grupo de pesquisa? Encontre-o e solicite sua
                entrada
              </p>
            </div>
            <div class="img-btn mx-3">
              <img src="../assets/search.svg" alt="Lupa" />
            </div>
          </div>
        </button>
      </div>

      <div class="col-sm">
        <button class="btn btn-primary px-3 py-3">
          <div class="d-flex justify-content-center align-items-center">
            <div class="text-start">
              <p class="fw-bold mb-1">Criar Grupos de Pesquisa</p>
              <p>
                Crie o seu grupo de pequisa. É possível gerenciar dados das instituições.
              </p>
            </div>
            <div class="img-btn mx-3">
              <img src="../assets/plus-circle.svg" alt="Adicionar" />
            </div>
          </div>
        </button>
      </div>

      <div class="col-sm-2">
        <img class="img-fluid" src="../assets/search-flat.png" alt="Adicionar" />
      </div>
    </div>

    <div class="row mb-5">
      <div class="col">
        <button class="btn btn-light d-flex align-items-center">
          <img class="me-2" src="../assets/help-circle.svg" alt="alert" />
          <span>Entenda</span>
        </button>
      </div>
    </div>

    <div class="row mb-3">
      <div class="col">
        <h3>
          Você não pertence a <span class="fw-bold">nenhum</span> grupo de
          pesquisa.
        </h3>
      </div>
    </div>

    <div class="row">
      <div class="col">
        <!-- <label for="filterGruposPesquisa" class="me-3">Filtrar por:</label>
        <select class="form-select form-select-sm d-inline" name="filterGruposPesquisa" id="filterGruposPesquisa">
          <option value="" selected disabled>Todos</option>
          <option value="">Estado</option>
        </select> -->
      </div>
    </div>

    <div class="row">
      <div class="col d-flex justify-content-end">
        <img class="img-max-size-40vw" src="../assets/search-flat.png" alt="Fundo">
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  background: linear-gradient(180deg, #d5e8fe 0%, rgba(255, 255, 255, 0) 100%),
    #fefefe !important;
  margin: 0;
  padding: 0;
  min-height: 100vh;
}

@import url("https://fonts.googleapis.com/css?family=Hind:400,700");

html {
  font-size: 106.3%;
} /*17px*/

body {
  background: white;
  font-family: "Hind", sans-serif;
  font-weight: 400;
  line-height: 1.75;
  color: #000000;
}

p {
  margin-bottom: 1rem;
}

h1,
h2,
h3,
h4,
h5 {
  margin: 3rem 0 1.38rem;
  font-family: "Hind", sans-serif;
  font-weight: 700;
  line-height: 1.3;
}

h1 {
  margin-top: 0;
  font-size: 3.157rem;
}

h2 {
  font-size: 2.369rem;
}

h3 {
  font-size: 1.777rem;
}

h4 {
  font-size: 1.333rem;
}

small,
.text_small {
  font-size: 0.75rem;
}

button {
  padding: 1rem;
  text-align: left;
  background: aliceblue;
  border: none;
  border-radius: 10px;
}

.img-btn img {
  max-width: 48px;
}

.btn-primary {
  background: #0d9f9f !important;
  border: 1px solid #0d9f9f !important;
}

.btn-primary:hover {
  background: #0d9f9f !important;
  border: 1px solid #0d9f9f !important;
}

.btn-light {
  background: #f5f5f5 !important;
  border: 1px solid #626262 !important;
  box-sizing: border-box !important;
  border-radius: 10px !important;
}

.btn p {
  margin: 0;
}

.img-max-size-40vw{
  max-width: 40vw;
}
</style>
