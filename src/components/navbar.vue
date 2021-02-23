<template>
  <nav class="navbar navbar-expand-lg navbar-dark  white">
    <div class="container">

      <a class="navbar-brand text-dark" href="http://sbuh.se/">SBUH <strong class="my-dot"></strong></a>

      <button class="navbar-toggler theme-bg" type="button" data-toggle="collapse" data-target="#navbarText"
        aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link text-dark" href="#Boka">Boka</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#foton">Foton</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#maskiner">Maskiner</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#prislista">Prislista</a>
          </li>
        </ul>
        <a href="mailto:leif@sbuh.se" class="btn theme-bg btn-circle btn-md"><i class="fas fa-envelope fa-2x text-white mail-icon"></i></a> 
      </div>

    </div>
  </nav>
</template>

<script>
export default {

}
</script>


<style scoped>
.my-dot {
  margin-left: -0.5rem;
  margin-bottom: -0.05rem;
  height: 7px;
  width: 7px;
  background-color: var(--theme-color);
  border-radius: 50%;
  display: inline-block;
}

.border-bottom {
  color: blue !important;
}

.mail-icon {
  margin-left: 1px;
}

.btn-circle.btn-md { 
  width: 50px; 
  height: 50px; 
  padding: 14px 10px; 
  border-radius: 25px; 
  font-size: 10px; 
  text-align: center; 
} 

.navbar-brand {
  font-weight: 800;
  font-size: 26px;
  font-family: 'Roboto Slab', serif;
}.navbar-brand:hover {
  color: var(--theme-color) !important;
}

.nav-link {
  font-weight: 500;
  font-size: 18px;
} .nav-link:hover {
  color: var(--theme-color) !important;
}

.nav-item {
  margin-right: 10px;
}

.btn {
  font-weight: 600;
  font-size: 16px;
  padding: 10px 18px 10px 18px;
  border-radius: 6px;
  margin-left: 0;
}

.navbar {
  box-shadow: 0px 5px 10px 10px rgba(0, 0, 0, 0.219);  
}

</style>
