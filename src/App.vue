<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-custom">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <font-awesome-icon icon="baseball-ball" />
          Jokatu
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <router-link class="nav-link" to="/" exact>Mon compte</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about">Trouver un joueur</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact">Trouver une partie</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
};
</script>

<style>
/* Importation du fichier style.css */
@import './style.css';

/* Vous pouvez ajouter des styles personnalisés ici */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
}
</style>
