<template>
<div class="bg-color1 pb-5 pt-3" id="maskiner&prislista">
  <div class="bg-color mb-5">
    <div class="pt-5 pb-2">
        <h1 class="text-center text-white">Maskiner</h1>
    </div>
    <div class="container">
      <div class="row mt-5 py-4 pt-4">
        <!-- CARD START -->
        <div class="col-md-4 pb-3 text-white">
          <div class="card mb-5">
            <div class="card-body card-body-cascade text-left bg-cards">
            <div class="view view-cascade overlay z-depth-2">
              <img class="card-img-top image-size" src="../assets/gulful.jpg" alt="Machine">
            </div>
              <h3 class="mb-3 font-weight-bold mt-3 theme-color">YC18-2</h3>             
              <p class="card-text text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae quibusdam culpa, omnis labore ipsum incidunt eveniet temporibus repellat atque!
                <br> <br>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, nobis?
                <br>
              </p>
              <a href="#Boka" class="btn btn-md">TILL BOKNINGEN
                <i class="fas fa-arrow-down ml-1"></i>
              </a>
            </div>
          </div>
        </div>
        <!-- CARD START -->
        <!-- CARD START -->
        <div class="col-md-4 pb-3 text-white">
          <div class="card mb-5">
            <div class="card-body card-body-cascade text-left bg-cards">
            <div class="view view-cascade overlay z-depth-2">
              <img class="card-img-top image-size" src="../assets/gulful.jpg" alt="Machine">
            </div>
              <h3 class="mb-3 font-weight-bold mt-3 theme-color">YC18-2</h3>             
              <p class="card-text text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae quibusdam culpa, omnis labore ipsum incidunt eveniet temporibus repellat atque!
                <br> <br>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, nobis?
                <br>
              </p>
              <a href="#Boka" class="btn btn-md">TILL BOKNINGEN
                <i class="fas fa-arrow-down ml-1"></i>
              </a>
            </div>
          </div>
        </div>
        <!-- CARD START -->
        <!-- CARD START -->
        <div class="col-md-4  pb-3 text-white">
          <div class="card mb-5">
            <div class="card-body card-body-cascade text-left bg-cards">
            <div class="view view-cascade overlay z-depth-2">
              <img class="card-img-top image-size" src="../assets/gulful.jpg" alt="Machine">
            </div>
              <h3 class="mb-3 font-weight-bold mt-3 theme-color">YC18-2</h3>             
              <p class="card-text text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae quibusdam culpa, omnis labore ipsum incidunt eveniet temporibus repellat atque!
                <br> <br>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, nobis?
                <br>
              </p>
              <a href="#Boka" class="btn btn-md">TILL BOKNINGEN
                <i class="fas fa-arrow-down ml-1"></i>
              </a>
            </div>
          </div>
        </div>
        <!-- CARD START -->
      </div>
    </div>
  </div>

  <div class="jumbotron jumbotron-fluid my-3">
    <div class="container">
      <div class="text-center">
        <h1 class="">Prislista</h1>
        <p class="lead">Alla priser nedan är exclusive moms.</p>
      </div>


      <div class="row">
        <div class="p-2 col-12 col-md-6">
          <table>
              <th class="title"><i class="fas fa-clock theme-color"></i> Tid</th>
              <th class="title">Pris</th>
              <tbody>
                <tr>
                  <td>1 Dygn</td>
                  <td>1000 kr</td>
                </tr>
                <tr>
                  <td>Fredag eftermiddag - Söndag kväll</td>
                  <td>2000 kr</td>
                </tr>
                <tr>
                  <td>1 Vecka (Hyr 7 dygn till priset av 6 dygn)</td>
                  <td>6000 kr</td>
                </tr>
                <tr>
                  <td></td>
                  <td></td>
                </tr>
              </tbody>
          </table>
        </div>
        
        <!-- LEVERANS -->
        <div class="p-2 col-12 col-md-6">
          <table>
              <th class="title"><i class="fas fa-truck theme-color"></i> Leverans eller Hämtning</th>
              <th class="title">Pris</th>
              <tbody>
                <tr>
                  <td>Norrort</td>
                  <td>600 kr</td>
                </tr>
                <tr>
                  <td>Söderort</td>
                  <td>900 kr</td>
                </tr>
                <tr>
                  <td> </td>
                  <td class="text-white">6000 kr</td>
                </tr>
                <tr>
                  <td></td>
                  <td></td>
                </tr>
              </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>

.btn {
  background: linear-gradient(to right, rgb(243, 141, 7), rgb(247, 91, 1));
  font-weight: 600;
  border-radius: 10px;
  font-size: 14px;
  letter-spacing: 1.5px;
  margin: 0;
}

h1 {
  font-weight: bold;
}

.title {
  font-weight: 600;
  font-size: 16px;
}

table {
  width:100%;
}

tr {
  border-top:1px solid black
}

/* thead tr {
  border-width:2px;
} */

th {
  text-align:left;
}

th,td {
  padding:1em;
}

/* .jumbotron {
  background-color: rgb(19, 19, 19);
  color: white;
} */



.image-size {
  height: 250px;
}

.card {
  background-color: transparent;
  border-radius: 10px;
}

.card-text {
  font-size: 16px !important;
}

.card-body {
  border-radius: 6px;
  min-height: 525px;
    
}

.view {
  margin-top: -4rem;
  border-radius: 5px;  
}

.bg-cards {
  background: linear-gradient(to bottom, rgb(32, 32, 32), rgb(19, 19, 19));
  box-shadow: 0px 5px 20px 10px rgba(0, 0, 0, 0.219);  
}

.bg-color {
  background-color: rgba(0, 0, 0, 0.836);
  box-shadow: 0px 5px 20px 10px rgba(0, 0, 0, 0.219); 
}
.bg-color1 {
  background-color: rgba(230, 228, 228, 0.192);
}

</style>