<template>
    <div class="container-fluid bgSambutan pb-5">
    <div class="font text-center">
      <p>Biodata</p>
    </div>
    <div class="row">
      <div class="col-xxl-4">
        <img src="/gambar/RadiMT.png" class="img-fluid mx-auto d-block" style="height: 500px;"/>
      </div>
      <div class="col-xxl-8 text-sambutan">
        <p>Nama : Radi Maulana Tsaqif</p>
        <p>Umur : 17</p>
        <p>Jenis Kelamin : Laki-Laki</p>
        <p>Kelas : XII PPLG 1</p>
        <p>Asal Sekolah : SMK Negeri 4 Tasikmalaya</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Beau+Rivage&display=swap');

.bgSambutan {
  background-color: #EAE7DD;
  display: flex;
  flex-direction: column;
  min-height: 87.7vh;
  flex: 1;
}

.bgSambutan .font p {
  font-size: 4rem;
  padding-top: 20px;
  font-weight: bold;
  font-family: "Beau Rivage", serif;
}

.bgSambutan .text-sambutan {
  padding-top: 60px;
  font-family: "IBM Plex Sans Condensed", serif;
  font-weight: 400;
  font-style: italic;
}


</style>