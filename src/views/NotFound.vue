<template>
  <div>
    <!-- CONTENIDO PARA LA VISTA DE RUTAS INEXISTENTES -->
    <header
      class="masthead"
      style="background-image: url('/assets/img/chevrolet-blazer.jpg')"
    >
      <div class="overlay"></div>
      <div class="container">
        <div class="row">
          <div class="col-md-10 col-lg-8 mx-auto">
            <div class="post-heading">
              <h1><strong>La página que busca no existe</strong></h1>
            </div>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "NotFound",
};
</script>

<style scoped>
  header {
      margin-top: 50px;
  }
  .masthead{
    width: 100%;
    height: 700px;
    background-size: cover;
    background-repeat: no-repeat;
    color: white;
  }
  footer {
    text-align: center;
  }
</style>