<template>
  <div id="app" class="container">
    <main role="main">
      <div class="jumbotron">
        <div class="container">
          <h1 class="display-3">Bootstrap + Vue + Sass</h1>
          <p>
            <a
              class="btn btn-success btn-lg"
              href="http://vuejs.org"
              role="button"
            >Documentación Vue</a>
          </p>
          <p>
            <a
              class="btn btn-danger btn-lg"
              href="https://sass-lang.com"
              role="button"
            >Documentación Sass</a>
          </p>
          <p>
            <a
              class="btn btn-primary btn-lg"
              href="https://getbootstrap.com"
              role="button"
            >Documentación Bootstrap</a>
          </p>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <h2>Sección 1</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <p>
              <a class="btn btn-secondary" href="#" role="button">Botón »</a>
            </p>
          </div>
          <div class="col-md-4">
            <h2>Sección 2</h2>
            <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui.</p>
            <p>
              <a class="btn btn-secondary" href="#" role="button">Botón »</a>
            </p>
          </div>
          <div class="col-md-4">
            <h2>Sección 3</h2>
            <p>Donec sed odio dui. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
            <p>
              <a class="btn btn-secondary" href="#" role="button">Botón »</a>
            </p>
          </div>
        </div>

        <hr>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {}
};
</script>

<style lang="scss">
@import "./styles/custom.scss";
@import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>
