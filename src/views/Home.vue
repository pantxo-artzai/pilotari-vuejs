<template>
  <div class="full-screen-background d-flex align-items-center justify-content-center text-center">
    <div>
      <h1 class="display-4 font-weight-bold text-white">Il est où le quatrième?</h1>
      <p class="lead text-white">Le quatrième joueur est à portée de clic!</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
}
</script>

<style scoped>
.full-screen-background {
  background-image: url('https://www.pilota-ttiki.com/wp-content/uploads/2023/01/IMG_5474.jpg'); /* Remplacez par l'URL de votre image */
  background-size: cover;
  background-position: center;
  width: 100vw;
  height: 100vh;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
