<template>
    <div class="bg-img">
    <div class="elfsight-app-951e9897-de65-41e1-81c3-8286f0c09ceb"></div>
        <div class="my-overlay">
            <section class="text-center">
                <div class="col-md-12 p-0">
                    <div class="card">
                        <div class="text-white text-center align-items-center px-4 px-md-5 my-margin-top">
                            <div>
                                <h1 class="py-1 font-weight-bold animated fadeIn" style="animation-delay: 700ms;">
                                    <strong class="SBUH">Sollentuna Bygguthyrning</strong>
                                </h1>
                                <p id="slogan" class="animated fadeIn" style="animation-delay: 800ms;">
                                  Vi erbjuder smidiga grävare där du inte behöver oroa dig för att tomten ska bli förstörd. 
                                  <br> Finns även möjlighet till att hyra förare!
                                </p>
                                <a href="#Boka" class="btn animated fadeInUp" style="animation-delay: 900ms;">BOKA <i class="fas fa-pen ml-1"></i></a>
                                <a href="#Priser" class="btn animated fadeInUp" style="animation-delay: 900ms;">Priser <i class="fas fa-tag ml-1"></i></a>
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
  margin: 10px;
  color: white;
  padding: 15px 35px
}

.btn:hover {
  box-shadow: 0px 0px 20px 2px rgb(243, 141, 7);  
  color: white;
}

.SBUH {
  font-size: 35px;
}

#slogan {
  font-size: 22px;
}

.bg-img {
  background-image: url(../assets/bannerMobile.jpg);
  background-size: cover;
}

@media (min-width: 768px) {  
  .SBUH {
    font-size: 50px;
  }
  #slogan {
    font-size: 28px;
  }
  .bg-img {
    background-image: url(../assets/banner.jpg);
  }
}

.my-margin-top {
  margin-top: 13%;
}

.card {
  background-color: transparent;
  padding-bottom: 15%;
}

.my-overlay {
  background: rgba(0, 0, 0, 0.781);
}

</style>
