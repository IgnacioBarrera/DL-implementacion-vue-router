<template>
  <div>
        <!-- CONTENIDO PARA LA VISTA DE PORTADA -->
    <header class="masthead" style="background-image:url('assets/img/home-bg.jpg');">
        <div class="overlay"></div>
        <div class="container">
            <div class="row">
                <div class="col-md-10 col-lg-8 mx-auto">
                    <div class="site-heading">
                        <h1>V8</h1><span class="subheading">Noticias y reseñas de automóviles</span></div>
                </div>
            </div>
        </div>
    </header>
    <div class="container">
        <div class="row">
            <div class="col-md-10 col-lg-8">
                <div class="post-preview">
                    <router-link to="/post/1">
                        <h2 class="post-title"><strong>Chevrolet presenta la totalmente nueva Blazer</strong></h2>
                        <h3 class="post-subtitle">Llega&nbsp;como la primera SUV deportiva de la marca</h3>
                    </router-link>
                </div>
                <hr>
            </div>
        </div>
    </div>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-md-10 col-lg-8 mx-auto">
                    <ul class="list-inline text-center">
                        <li class="list-inline-item"><span class="fa-lg"><font-awesome-icon :icon="['fab','facebook']"/></span></li>
                        <li class="list-inline-item"><span class="fa-lg"><font-awesome-icon :icon="['fab','twitter']"/></span></li>
                        <li class="list-inline-item"><span class="fa-lg"><font-awesome-icon :icon="['fab','github']"/></span></li>
                    </ul>
                    <p class="text-muted copyright">Copyright&nbsp;©&nbsp;V8 - 2018</p>
                </div>
            </div>
        </div>
    </footer>
  </div>
</template>

<script>

export default {
  name: 'Portada',
}
</script>

<style scoped>
    header {
        margin-top: 50px;
    }
    .masthead {
        margin-top: 50px;
        height: 600px;
        color: black;
        text-align: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
    footer {
        text-align: center;
    }
</style>
