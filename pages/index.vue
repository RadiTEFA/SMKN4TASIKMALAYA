<template>
    <div class="text-container text-center text-white">
      <p class="text-white">"SMK bisa, SMK hebat, SMK Negeri 4 Tasikmalaya bisa hebat".</p>
    </div>
    <div class="overflow-hidden text-center">
      <div class="fw-bolder text-center p-5  bg-secondary Text-Sambutan">
        <p>Sambutan Kepala Sekolah</p>
      </div>
      <div class="row bg-secondary">
        <div class="col-md-4 Kepsek">
          <img src="/gambar/Kurniawan.png" class="img-fluid" />
        </div>
        <div class="col-md-8 bg-secondary" style="font-size:1.2rem; font-family: Helvetica Neue;">
          <p>Assallamuallaikum Wr.Wb</p>
          <br /><br />
          <p>Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-nya. dan atas perkenan-Nya kami pula dapat menghadirkan Website SMK Negeri 4 Tasikmalaya ini.</p><br><br>
          <p>Kami berharap dengan adanya Website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturahmi antar sekolah dengan masyarakat demi kemajuan kira bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.</p><br><br>
          <p>Wassallamuallaikum Wr.wb</p><br><br>
        </div>
      </div>
    </div>
    <div>
      <div class="main-content">
        <div class="info-box">
            <h2>Siswa</h2>
            <p>1116</p>
        </div>
        <div class="info-box">
            <h2>Guru</h2>
            <p>60</p>
        </div>
        <div class="info-box">
            <h2>Staf TU</h2>
            <p>10</p>
        </div>
        <div class="info-box">
            <h2>Ruangan</h2>
            <p>34</p>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-4 row-cols-xl-5 row-cols-xxl-6">
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
        <div class="col">
          <img src="/gambar/EC1.jpg" class="img-thumbnail" alt="...">
        </div>
      </div>
    </div>
    <div>
      <button type="button" class="btn btn-link">
        <a href="https://smkn4tasikmalaya.vercel.app/Galery">Lihat selengkapnya</a>
      </button>
    </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Beau+Rivage&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Tinos&display=swap');

  body{
    background-color: pink;
  }

  .navbar-toggler-icon {
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3E%3Cpath stroke='rgba(255, 255, 255, 1)' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
  }
  .Kepsesk {
    width: 300px;
    mix-blend-mode: multiply;
  }
  .text-container {
  background-image: url('/gambar/GerbangSekolah.png');
  background-size: cover; /* Sesuaikan ukuran gambar */
  background-position: center; /* Posisikan gambar di tengah */
  width: 100%; /* Lebar kontainer */
  height: 400px;
  display: flex; /* Gunakan flexbox untuk memusatkan teks */
  justify-content: center; /* Pusatkan secara horizontal */
  align-items: center; /* Pusatkan secara vertikal */
  color: white;
  font-size: 2rem;
  font-weight: bold;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
  filter: brightness(50%) contrast(100%); /* Sesuaikan nilai */
  font-family: "Lato", serif;
}
.Text-Sambutan {
  font-family: "Oswald", serif;
  font-size: 3rem;
  font-optical-sizing: auto;
  font-style: normal;
}
.main-content {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    margin: 20px;
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
    width: 410px;
}

/* Gaya judul info box */
.info-box h2 {
    font-size: 30px;
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
</style>
