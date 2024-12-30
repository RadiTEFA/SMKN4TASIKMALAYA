<template>
  <div class="d-flex flex-column bg-secondary">
    <div class="content container my-3">
      <div class="row py-3 font">
        <div class="col">
          <h4 class="text-white text-center">Patroli Keamanan Sekolah</h4>
        </div>
      </div>
      <div class="accordion" id="accordionPanelsStayOpenExample">
        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingOne">
            <button class="accordion-button" type="button" data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true"
              aria-controls="panelsStayOpen-collapseOne">
              1. Pembina Ekstrakulikuler
            </button>
          </h2>
          <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show"
            aria-labelledby="panelsStayOpen-headingOne">
            <div class="accordion-body">
              <div class="text-center">
                <img src="/gambar/Kurniawan.png" class="rounded" alt="...">
              </div>
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="false"
              aria-controls="panelsStayOpen-collapseTwo">
              2. Anggota
            </button>
          </h2>
          <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse"
            aria-labelledby="panelsStayOpen-headingTwo">
            <div class="accordion-body">
              <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse
              plugin adds the appropriate classes that we use to style each element. These classes control the overall
              appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom
              CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the
              <code>.accordion-body</code>, though the transition does limit overflow.
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false"
              aria-controls="panelsStayOpen-collapseThree">
              3. Prestasi
            </button>
          </h2>
          <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse"
            aria-labelledby="panelsStayOpen-headingThree">
            <div class="accordion-body">
              <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse
              plugin adds the appropriate classes that we use to style each element. These classes control the overall
              appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom
              CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the
              <code>.accordion-body</code>, though the transition does limit overflow.
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="panelsStayOpen-headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false"
              aria-controls="panelsStayOpen-collapseThree">
              4. Galery Ekstrakulikuler
            </button>
          </h2>
          <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse"
            aria-labelledby="panelsStayOpen-headingThree">
            <div class="accordion-body">
              <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse
              plugin adds the appropriate classes that we use to style each element. These classes control the overall
              appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom
              CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the
              <code>.accordion-body</code>, though the transition does limit overflow.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Beau+Rivage&display=swap');

.font h4 {
  font-size: 75px;
  margin-bottom: 10px;
  color: #007bff;
  font-family: "Beau Rivage", serif;
}
</style>
