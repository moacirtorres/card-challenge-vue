<template>

    <div class="app d-flex justify-content-center align-items-center flex-mobile">
        <div class="card mb-3 card-style">
            <div class="row">
              <div class="col-lg-6">
                <div class="card-body mx-5">
                  <h5 class="card-title mt-5 mx-2"  style="font-family: 'Inter', sans-serif; font-size: 35px;">Get <span style="color: hsl(277, 64%, 61%);">insights</span> that help your business grow.</h5>
                  <p class="card-text my-4 mx-2" style="font-family: 'Lexend Deca', sans-serif; font-size: 14px;">Discover the benefits of data analytics and make better decisions regarding revenue, customar experience, and overall efficiency.</p>
                  <div class="row mt-5" style="font-size: 25px">
                      <div class="col-lg-4 d-flex flex-column"><span>10k+</span><span style="font-size: 13px;">companies</span></div>
                      <div class="col-lg-4 d-flex flex-column"><span>314</span><span style="font-size: 13px;">templates</span></div>
                      <div class="col-lg-4 d-flex flex-column"><span>12M+</span><span style="font-size: 13px;">queries</span></div>
                  </div>
                </div>
              </div>
              <div class="d-flex col-lg-6 g-0">
                <img src="../assets/images/image-header-desktop.jpg" class="img-fluid rounded-1 opacity-purple" alt="Imagem">
              </div>
            </div>
          </div>
    </div>

</template>


<script>

import "bootstrap";

    export default {
        name: 'card-principal',
    }

</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Lexend+Deca&display=swap');

* {
    font-family: 'Inter', sans-serif;
    font-family: 'Lexend Deca', sans-serif;
}

.app {
    background-color: hsl(233, 47%, 7%);
    height: 100vh;
    width: 100vw;
}

.card-style {
  max-width: 1000px;
  background-color: hsl(244, 38%, 16%) !important;
  color: hsl(0, 0%, 100%);
  border-radius: 1rem !important;
}



@media screen and (max-width: 500px) {
    .row {
          flex-direction: column-reverse;
    }
    
}


</style>