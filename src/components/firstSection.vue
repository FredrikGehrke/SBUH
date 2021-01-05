<template>
    <div class="bg-img">
        <div class="my-overlay">
            <section class="text-center">
                <div class="col-md-12 p-0">
                    <div class="card">
                        <div class="text-white text-center align-items-center py-5 px-4 px-md-5 my-margin-top">
                            <div>
                                <h1 class="py-1 font-weight-bold animated fadeIn" data-animation-delay="800ms">
                                    <strong>Sollentuna Bygguthyrning</strong>
                                </h1>
                                <p id="slogan" class="pb-2 animated fadeIn">Behöver du hyra en liten smidig grävare för grävjobb där du inte vill att hela tomten skall bli förstörd?
                                </p>
                                <a href="#Boka" class="btn animated fadeIn" style="animation-delay: 900ms;">BOKA <i class="fas fa-pen ml-1"></i></a>
                                <a href="#Kontakt" class="btn animated fadeIn" style="animation-delay: 900ms;">Kontakt <i class="fas fa-envelope ml-1"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </div>
</template>

<style scoped>

.btn {
  background: linear-gradient(to right, rgb(243, 141, 7), rgb(247, 91, 1));
  border-radius: 10px;
  font-weight: bold;
  font-size: 16px;
  letter-spacing: 1.5px;
}

.btn:hover {
  background: linear-gradient(to right, rgb(0, 200, 81), rgb(1, 102, 42));
  box-shadow: 0px 0px 20px 2px rgba(0, 200, 80, 0.562);  
  color: white;
}

#slogan {
  font-size: 24px;
}

.my-margin-top {
  margin-top: 8%;
}

.card {
  background-color: transparent;
  padding-bottom: 9%;
}

.my-overlay {
  background: rgba(0, 0, 0, 0.815);
}

.bg-img {
  background-image: url(../assets/excavator.jpg);
  background-size: cover;
}


</style>
