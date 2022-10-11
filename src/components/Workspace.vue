<template>
  <section class="section is-medium has-background-dark" id="portfolio">
    <div class="container is-align-content-start">
      <div class="section-heading pt-5">
        <h3
          class="
            title
            is-2
            has-text-centered
            is-family-code
            has-text-weight-semibold has-text-grey-light
          "
        >
          Projetos
        </h3>
      </div>
      <br />

      <div class="container portfolio-container">
        <div class="columns">
          <div class="column is-4">
            <div class="card">
              <header class="card-header">
                <p class="card-header-title">
                  <span> Busca Filmes </span>
                </p>
              </header>
              <div class="card-content">
                <figure class="image">
                  <img
                    src="../assets/images/moogle.png"
                    alt="Admin template screenshot"
                  />
                </figure>
              </div>
              <footer class="card-footer">
                <a href="https://buscafilmes.vercel.app/#/" class="card-footer-item">Preview</a>
                <a href="https://github.com/rodolphorss/buscafilmes" class="card-footer-item">
                  SourceCode
                </a>
              </footer>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "ProjetosRodolpho",
});
</script>

<style scoped>
</style>
