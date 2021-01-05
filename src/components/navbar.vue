<template>
  <nav class="navbar navbar-expand-lg navbar-dark white">
    <div class="container">

      <a class="navbar-brand text-dark" href="#">SBUH</a>

      <button class="navbar-toggler theme-bg" type="button" data-toggle="collapse" data-target="#navbarText"
        aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Boka</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Kontakt</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Foton</a>
          </li>
        </ul>
        <button type="button" class="btn theme-bg text-white">Boka</button>
        <a id="mail-icon" href="mailto:fredrikg@nomea.se"><i class="fas fa-envelope fa-2x theme-color px-2"></i></a>
      </div>

    </div>
  </nav>
</template>

<script>
export default {

}
</script>


<style scoped>

.navbar-brand {
  font-weight: 800;
  font-size: 26px;
  font-family: 'Roboto Slab', serif;
}

.nav-link {
  font-weight: 500;
  font-size: 18px;
} .nav-link:hover {
  color: var(--theme-color) !important;
}

.btn {
  font-weight: 600;
  font-size: 16px;
  padding: 10px 18px 10px 18px;
  border-radius: 6px;
  margin-left: 0;
}



</style>
