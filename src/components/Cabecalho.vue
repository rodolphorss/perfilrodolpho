<template>
  <nav class="navbar is-black is-fixed-top">
    <div class="navbar-brand">
      <img src="../assets/rlogo.png" width="100" height="100" />
    </div>
    <div class="navbar-menu">
      <div class="navbar-end">
        <a class="navbar-item" href="#sobre">
          <span class="icon">
            <i class="fas fa-info has-text-grey-light"></i>
          </span>
          <span is-family-code>Informações</span>
        </a>
        <a class="navbar-item" href="#portfolio">
          <span class="icon">
            <i class="fas fa-folder-open has-text-grey-light"></i>
          </span>
          <span is-family-code>Projetos</span>
        </a>
        <a class="navbar-item" href="https://www.facebook.com/rodolpho.souza.9/">
          <span class="icon">
            <i class="fab fa-facebook mx-1 has-text-grey-light"></i>
          </span>
        </a>
        <a class="navbar-item" href="https://www.linkedin.com/in/rodolpho-souza-santos-58531641/">
          <span class="icon">
            <i class="fab fa-linkedin mx-1 has-text-grey-light"></i>
          </span>
        </a>
        <a class="navbar-item" href="https://www.instagram.com/rodolpho.rss/">
          <span class="icon">
            <i class="fab fa-instagram mx-1 has-text-grey-light"></i>
          </span>
        </a>
      </div>
    </div>
  </nav>

  <section class="hero is-dark is-fullheight">
    <div class="hero-body">
      <div class="container">
        <h1 class="title is-3 has-text-grey-light is-family-code">
          Existem 10 tipos de pessoas no mundo:
        </h1>
        <h2 class="title is-2 is-family-code">
          As que entendem binário e as que não entendem 😅
        </h2>
      </div>
    </div>
  </section>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "BarraDeNavegacao",
});
</script>
