<template>
  <header>
    <section id="home" class="hero is-fullheight">
      <div class="hero-head">
        <b-navbar transparent wrapper-class="container" type="is-dark" spaced>
          <template slot="end">
            <b-navbar-item href="#">Acerca</b-navbar-item>
            <b-navbar-item href="#">Tecnologías</b-navbar-item>
            <b-navbar-item href="#">Proyectos</b-navbar-item>
            <b-navbar-item href="#">Contacto</b-navbar-item>
          </template>
        </b-navbar>
      </div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <h5 class="is-size-5 has-text-white">Hola, soy</h5>
          <h1 class="title is-1 has-text-weight-medium has-text-white">Daniel Rodríguez</h1>
          <h2 class="subtitle is-3 has-text-aqua">Ing. en Tecnologías de la Información</h2>

          <div class="block">
          <a class="mx-3">
            <b-icon 
              pack="fab"
              icon="linkedin-in"
              size="is-medium"
              type="is-white"
            ></b-icon>
          </a>
          <a class="mx-3">
            <b-icon
              pack="fab"
              icon="github"
              size="is-medium"
              type="is-white"
            ></b-icon>
          </a>
          <a class="mx-3">
            <b-icon
              pack="far"
              icon="envelope"
              size="is-medium"
              type="is-white"
            ></b-icon>
          </a>
          </div>
          <b-button type="is-aqua" size="is-medium" class="has-text-white" outlined>Contáctame</b-button>
        </div>
      </div>

    </section>
  </header>
</template>

<style>
#home {
  background: url("../assets/landscape.jpg");
  background-size: cover;
}

.mx-3 {
  margin: 0 1rem 0 1rem;
}


</style>