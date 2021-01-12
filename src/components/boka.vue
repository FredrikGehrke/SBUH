<template>
  <div class="container-fluid pb-5 dark-bg">
    <div class="container">
      <div class="text-center text-white">
        <h1 class="pt-5">Boka!</h1>
        <hr class="mb-4" />
        <h6>Skicka gärna din bokning eller meddelande till oss här</h6>
      </div>
      <div class="d-flex">
        <div class="col-md-6 mt-5 text-white">
          <i class="fas fa-map-marker-alt fa-2x mt-3 theme-color mb-2"></i>
          <p class="font-weight-bold mb-0 text-white">
            724 63 Stockholm, Sverige eller Finland
          </p>

          <i class="fas fa-phone-square-alt fa-2x theme-color mt-5"></i>
          <p class="font-weight-bold mb-0">070-2200491</p>
          <p class="font-weight-bold mb-0">073-5745403</p>
          <p class="font-weight-bold mb-0">0762-577951</p>

          <i class="fas fa-envelope fa-2x theme-color mt-5"></i>
          <p class="font-weight-bold mb-0">leif@sbuh.se</p>
        </div>
        <form class="col-md-6 mt-5 mx-auto text-white">
          <div class="form-group">
            <label for="exampleFormControlInput1">Namn</label>
            <input
              type="email"
              class="form-control"
              id="exampleFormControlInput1"
              placeholder="Ange ditt fullständiga namn"
            />
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Email address</label>
            <input
              type="email"
              class="form-control"
              id="exampleFormControlInput1"
              placeholder="name@example.com"
            />
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Telefonnummer</label>
            <input
              type="text"
              class="form-control"
              id="exampleFormControlInput1"
              placeholder="073-00 333 33"
            />
          </div>

          <div class="form-group">
            <label for="exampleFormControlTextarea1"
              >Skriv ditt meddelande</label
            >
            <textarea
              class="form-control"
              id="exampleFormControlTextarea1"
              rows="3"
            ></textarea>
          </div>
          <button type="submit" class="btn theme-bg text-white mb-2">
            Skicka
          </button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
hr {
  background: #f38d07 !important;
  width: 5%;
  margin: auto;
  padding: 1px;
}

.btn {
  background: linear-gradient(to right, rgb(243, 141, 7), rgb(247, 91, 1));
  font-weight: 600;
  font-size: 14px;
  margin: 0;
}

</style>