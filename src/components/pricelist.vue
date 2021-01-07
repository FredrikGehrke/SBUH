<template>
<div class="bg-color pb-5 pt-3" id="boka">
  <div class="container mt-5">
      <h1 class="theme-color text-center mb-5">Maskiner</h1>
      <div class="card-deck mb-5">
        <div class="card">
          <img class="card-img-top imgprice" src="../assets/gulful.jpg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title">YC18-2</h5>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
              <button class="btn text-white ml-0">BOKA VIA MAIL</button>
          </div>
        </div>
        <div class="card">
          <img class="card-img-top imgprice" src="../assets/gulful.jpg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title">YC18-2</h5>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
              <button class="btn text-white ml-0">BOKA VIA MAIL</button>
          </div>
        </div>
        <div class="card">
          <img class="card-img-top imgprice" src="../assets/gulful.jpg" alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title">YC18-2</h5>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
              <button class="btn text-white ml-0">BOKA VIA MAIL</button>
          </div>
        </div>
      </div>
  </div>

  <div class="jumbotron jumbotron-fluid">
    <div class="container">
      <h2 class="display-4">Prislista</h2>
      <p class="lead">Alla priser nedan är exclusive moms.</p>


      <div class="d-flex flex-row justify-content-between">
        <div class="p-2">
          <table>
            <thead>
              <tr>
                <th class="title">Tid</th>
                <th class="title">Pris</th>
              </tr>
            </thead>
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
        <div class="p-2">
          <table>
            <thead>
              <tr>
                <th class="title">Leverans eller Hämtning</th>
                <th class="title">Pris</th>
              </tr>
            </thead>
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
.bg-color {
  background-color: rgba(180, 180, 180, 0.144) !important;
}

.imgprice {
  height: 250px;
}

.btn {
  background: linear-gradient(to right, rgb(243, 141, 7), rgb(247, 91, 1));
  border-radius: 6px;
}

h1{
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
  border-top:1px solid var(--theme-color);
}

thead tr {
  border-width:2px;
}

th {
  text-align:left;
}

th,td {
  padding:1em;
}

</style>