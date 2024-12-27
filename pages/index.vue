<template>
    <div class="GambarAwal">
      <img src="/gambar/GerbangSekolah.png" class="img-fluid" width="100%" />
      <div class="text-overlay text-center">Selamat Datang<br>di Website sekolah</div>
    </div>
    <div class="overflow-hidden text-center">
      <div class="fw-bolder text-center p-5  bg-secondary" style="font-size: 3em; font-family: Helvetica Neue;">
       <p>Sambutan Kepala Sekolah</p>
      </div>
      <div class="row bg-secondary">
        <div class="col-md-4 Kepsek">
          <img src="/gambar/Kurniawan.png" class="img-fluid" />
        </div>
        <div class="col-md-8 bg-secondary"style="font-size:1em; pading-right:20px; font-family: Helvetica Neue;">
          <p>Assallamuallaikum Wr.Wb</p>
          <br /><br />
          <p>Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-nya. dan atas perkenan-Nya kami pula dapat menghadirkan Website SMK Negeri 4 Tasikmalaya ini.</p><br><br>
          <p>Kami berharap dengan adanya Website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturahmi antar sekolah dengan masyarakat demi kemajuan kira bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.</p><br><br>
          <p>Wassallamuallaikum Wr.wb</p><br><br>
        </div>
      </div>
    </div>
</template>
<style scoped>
  body{
    background-color: pink;
  }
  .GambarAwal {
    filter: brightness(50%) contrast(100%); /* Sesuaikan nilai */
  }

  .navbar-toggler-icon {
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3E%3Cpath stroke='rgba(255, 255, 255, 1)' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
  }
  .text-overlay {
    position: absolute;
    top: 50%; /* Tempatkan di tengah secara vertikal */
    left: 50%; /* Tempatkan di tengah secara horizontal */
    transform: translate(-50%, -50%); /* Sesuaikan teks untuk benar-benar berada di tengah */
    color: white; /* Warna teks */
    font-size: 2em; /* Ukuran font */
    font-family: "Helvetica Neue"; /* Jenis font */
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7); /* Efek bayangan pada teks */
  }
  .Kepsesk {
    width: 300px;
    mix-blend-mode: multiply;
  }
</style>
