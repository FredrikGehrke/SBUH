<template>
  <div class="container pb-4" id="foton">
    <div class="pt-5 pb-3">
      <div class="offset-md-3 col-md-6 col-12 text-center">
        <h3 class="title-color h1 font-weight-bold">Foton</h3>
      </div>
    </div>
    <div id="carouselExampleCaptions" class="carousel slide m-auto" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="3"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="4"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="5"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="../assets/E16.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Bobcat  E16</h5>
          <!-- <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p> -->
        </div>
      </div>
      <div class="carousel-item">
        <img src="../assets/TC29.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Terex TC29</h5>
          <!-- <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p> -->
        </div>
      </div>
      <div class="carousel-item">
        <img src="../assets/CormidiDumper.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Dumper</h5>
          <!-- <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p> -->
        </div>
      </div>
      <div class="carousel-item">
        <img src="../assets/TC29.2.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Terex TC29</h5>
          <!-- <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p> -->
        </div>
      </div>
      <div class="carousel-item">
        <img src="../assets/garage.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <!-- <h5>abelco xc15</h5> -->
          <!-- <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p> -->
        </div>
      </div>
      <div class="carousel-item">
        <img src="../assets/maskinslap.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <!-- <h5>abelco xc15</h5> -->
          <!-- <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p> -->
        </div>
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>

  </div>

</template>

<script>
export default {

}
</script>

<style scoped>

.carousel-item img{
  max-height: 700px !important;
}

.carousel {
  max-width: 80%;
}

.carousel-control-prev-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E") !important;
}

.carousel-control-next-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E") !important;
}

</style>