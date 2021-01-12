<template>
<div class="lighter-bg pb-5 pt-3" id="maskiner&prislista">
  <div class="dark-bg mb-5">
    <div class="pt-5 pb-3">
        <h1 class="text-center text-white">Maskiner</h1>
    </div>
    <div class="container">
      <div class="row mt-5 pt-4">
        <!-- CARD START -->
        <div class="col-md-4 pb-3">
          <div class="card mb-5">
            <div class="card-body card-body-cascade text-left bg-cards">
              <div class="view view-cascade overlay z-depth-2">
                <img class="card-img-top image-size" src="../assets/gulful.jpg" alt="Machine">
              </div>
              <div class="text-body">
                <h3 class="mb-3 font-weight-bold mt-3 theme-color">YC18-2</h3>             
                <p class="card-text text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae quibusdam culpa, omnis labore ipsum incidunt eveniet temporibus repellat atque!
                  <br> <br>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, nobis?
                  <br>
                </p>
              </div>
              <a href="#Boka" class="text-white bokaBtn btn-block">TILL BOKNINGEN
                <i class="fas fa-arrow-down ml-1"></i>
              </a>
            </div>
          </div>
        </div>
        <!-- CARD END -->
        <!-- CARD START -->
        <div class="col-md-4 pb-3">
          <div class="card mb-5">
            <div class="card-body card-body-cascade text-left bg-cards">
              <div class="view view-cascade overlay z-depth-2">
                <img class="card-img-top image-size" src="../assets/gulful.jpg" alt="Machine">
              </div>
              <div class="text-body">
                <h3 class="mb-3 font-weight-bold mt-3 theme-color">Abelco XC15</h3>             
                <p class="card-text text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae quibusdam culpa, omnis labore ipsum incidunt eveniet temporibus repellat atque!
                  <br> <br>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, nobis?
                  <br>
                </p>
              </div>
              <a href="#Boka" class="text-white bokaBtn btn-block">TILL BOKNINGEN
                <i class="fas fa-arrow-down ml-1"></i>
              </a>
            </div>
          </div>
        </div>
        <!-- CARD END -->
        <!-- CARD START -->
        <div class="col-md-4 pb-3">
          <div class="card mb-5">
            <div class="card-body card-body-cascade text-left bg-cards">
              <div class="view view-cascade overlay z-depth-2">
                <img class="card-img-top image-size" src="../assets/gulful.jpg" alt="Machine">
              </div>
              <div class="text-body">
                <h3 class="mb-3 font-weight-bold mt-3 theme-color">TB016</h3>             
                <p class="card-text text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae quibusdam culpa, omnis labore ipsum incidunt eveniet temporibus repellat atque!
                  <br> <br>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, nobis?
                  <br>
                </p>
              </div>
              <a href="#Boka" class="text-white bokaBtn btn-block">TILL BOKNINGEN
                <i class="fas fa-arrow-down ml-1"></i>
              </a>
            </div>
          </div>
        </div>
        <!-- CARD END -->
      </div>
    </div>
  </div>

  <div class="jumbotron jumbotron-fluid my-3" id="Priser">
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
                  <td class="">6000 kr</td>
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

.bokaBtn {
  background: linear-gradient(to bottom, rgb(243, 141, 7), rgb(247, 91, 1));
  padding: 15px;
  font-weight: 600;
  font-size: 14px;
  border-bottom-right-radius: 5px;
  border-bottom-left-radius: 5px;
  text-align: center;
} .bokaBtn:hover {
  box-shadow: 0px 0px 20px 2px rgb(243, 141, 7);  
  color: white;
}

/* .btn {
  background: linear-gradient(to right, rgb(243, 141, 7), rgb(247, 91, 1));
  font-weight: 600;
  border-radius: 10px;
  font-size: 14px;
  letter-spacing: 1.5px;
  margin: 0;
} */

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
  /* border-bottom: 4px solid var(--theme-color); */
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
  padding: 0;
}

.text-body {
  padding: 0px 20px 20px 20px;
}

.view {
  margin-top: -4rem;

  border-top-right-radius: 5px;
  border-top-left-radius: 5px;
}

.bg-cards {
  /* background: linear-gradient(to top, rgb(32, 32, 32), rgb(19, 19, 19)); */
  /* background: linear-gradient(to top, rgb(32, 32, 32), rgb(27, 27, 27)); */
    background: linear-gradient(to top, rgb(32, 32, 32), rgb(27, 27, 27));
  box-shadow: 0px 5px 20px 10px rgba(0, 0, 0, 0.219);  
}


</style>