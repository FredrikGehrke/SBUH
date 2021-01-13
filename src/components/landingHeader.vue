<template>
    <div class="bg-img">
    <div class="elfsight-app-951e9897-de65-41e1-81c3-8286f0c09ceb"></div>
        <div class="my-overlay">
            <section class="text-center">
                <div class="col-md-12 p-0">
                    <div class="card">
                        <div class="text-white text-center align-items-center py-5 px-4 px-md-5 my-margin-top">
                            <div>
                                <h1 class="py-1 font-weight-bold"> 
                                    <strong class="SBUH">Sollentuna Bygguthyrning</strong>
                                </h1>
                                <p id="slogan" class="pb-2">
                                  Vi erbjuder smidiga grävare där du inte behöver oroa dig för att tomten ska bli förstörd. 
                                  <br> Finns även möjlighet till att hyra förare!
                                </p>
                                <a href="#Boka" class="btn animated fadeIn" style="animation-delay: 900ms;">BOKA <i class="fas fa-pen ml-1"></i></a>
                                <a href="#Priser" class="btn animated fadeIn" style="animation-delay: 900ms;">Priser <i class="fas fa-tag ml-1"></i></a>
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
  padding: 10px 30px
}

.btn:hover {
  box-shadow: 0px 0px 20px 2px rgb(243, 141, 7);  
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
  background: rgba(0, 0, 0, 0.87);
}

.bg-img {
  background-image: url(../assets/excavator.jpg);
  background-size: cover;
}

</style>
