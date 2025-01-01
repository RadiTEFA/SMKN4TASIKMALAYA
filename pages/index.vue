<template>
  <div class="container-fluid bgSambutan">
    <div class="font text-center">
      <p>Sambutan Kepala Sekolah</p>
    </div>
    <div class="row">
      <div class="col-xxl-4">
        <img src="/gambar/Kurniawan.png" class="img-fluid mx-auto d-block" />
      </div>
      <div class="col-xxl-8 text-sambutan">
        <p>Assallamuallaikum Wr.Wb</p>
        <p>Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-nya. dan atas perkenan-Nya kami pula dapat menghadirkan Website SMK Negeri 4 Tasikmalaya ini.</p>
        <p>Kami berharap dengan adanya Website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturahmi antar sekolah dengan masyarakat demi kemajuan kira bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.</p>
        <p>Wassallamuallaikum Wr.wb</p>
      </div>
    </div>
  </div>
  <div class="container-fluid bgInformasi justify-content-center">
    <div class="judul-informasi text-center justify-content-center">
      <p>Informasi</p>
    </div>
    <div class="row Organisasi row-cols-1 row-cols-sm-2 row-cols-md-2 row-cols-lg-4 row-cols-xl-4 row-cols-xxl-4 g-3">
      <div class="col">
        <div class="info-box text-center">
          <h2>Siswa</h2>
          <p>1200</p>
        </div>
      </div>
      <div class="col">
        <div class="info-box text-center">
          <h2>Guru</h2>
          <p>60</p>
        </div>
      </div>
      <div class="col">
        <div class="info-box text-center">
          <h2>Staff TU</h2>
          <p>10</p>
        </div>
      </div>
      <div class="col">
        <div class="info-box text-center">
          <h2>Ruangan</h2>
          <p>34</p>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid bgGalery">
    <div class="judul-Galery text-center justify-content-center">
      <p>Galery</p>
    </div>
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 row-cols-xl-5 row-cols-xxl-5">
      <div class="col">
        <img src="/gambar/EC1.jpg" class="img-thumbnail" alt="...">
      </div>
      <div class="col">
        <img src="/gambar/EC1.jpg" class="img-thumbnail" alt="...">
      </div>
      <div class="col">
        <img src="/gambar/EC1.jpg" class="img-thumbnail" alt="...">
      </div>
      <div class="col">
        <img src="/gambar/EC1.jpg" class="img-thumbnail" alt="...">
      </div>
      <div class="col">
        <img src="/gambar/EC1.jpg" class="img-thumbnail" alt="...">
      </div>
    </div>
  </div>
  <div class="bgButton pt-3 pb-3">
    <a href="https://smkn4tasikmalaya.vercel.app/Galery/" class="view-more btn">Lihat Galery Lainnya</a>
  </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Beau+Rivage&display=swap');
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Condensed:ital@1&display=swap');

.bgSambutan {
  background-color: #EAE7DD;
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
  text-align: justify;
}

.bgInformasi {
  background-color: #EAE7DD;
}
.bgInformasi .judul-informasi p {
  font-size: 4rem;
  font-weight: bold;
  font-family: "Beau Rivage", serif;
}
/* Gaya info box */
.info-box {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    margin: 10px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Gaya judul info box */
.info-box h2 {
    font-size: 32px;
    margin-bottom: 10px;
    color: #007bff;
    font-family: "Beau Rivage", serif;
}

/* Gaya jumlah */
.info-box p {
    font-size: 24px;
    font-weight: bold;
    margin: 0;
    font-family: "Tinos", serif;
}

.bgGalery {
  background-color: #EAE7DD;
}

.bgGalery .judul-Galery p {
  font-size: 4rem;
  font-weight: bold;
  font-family: "Beau Rivage", serif;
}

.bgButton{
  background-color: #EAE7DD;
}

.bgButton .view-more {
  display: block;
  margin: 0 auto;
  padding: 12px 24px;
  background: #c0b283;
  color: white;
  border: none;
  border-radius: 4px;
  font-size: 14px;
  cursor: pointer;
  transition: all 0.3s ease;
  width: 175px;
}

.bgButton .view-more:hover {
  transform: scale(0.95);
  background: #c0b283;
  color: white;
}

@media (max-width: 575.98px) { 
  .info-box {
    max-width: 100px;
  }
}
@media (max-width: 767.98px) { 
  .info-box {
    max-width: 500px;
  }
}
@media (max-width: 991.98px) { 
  .info-box {
    max-width: 200px;
  }
}
@media (max-width: 1199.98px) { 
  .info-box {
    max-width: 200px;
  }
}
@media (max-width: 1399.98px) { 
  .info-box {
    max-width: 500px;
  }
}
</style>