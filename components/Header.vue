<template>
    <nav class="navbar sticky-top navbar-expand-lg bg">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="/gambar/LogoSMKN4TSK.png" width="37" height="40"/>
        </a>
        <a class="navbar-brand text-white mb-0 h1" href="#">SMK Negeri 4 Tasikmalaya</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="https://smkn4tasikmalaya.vercel.app/">Beranda</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://smkn4tasikmalaya.vercel.app/Profile">Profil Sekolah</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://smkn4tasikmalaya.vercel.app/Ekstrakulikuler">Ekstrakulikuler</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://smkn4tasikmalaya.vercel.app/Galery">Galery</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://smkn4tasikmalaya.vercel.app/Biodata/">Biodata</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>
<style scoped>
.bg {
  background-color: #99775C;
}

.nav-link {
  color: white;
  font-weight: bold;
}
.nav-link:hover {
  transform: scale(0.95);
  color: black;
  font-weight: bold;
}

.navbar-toggler-icon {
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3E%3Cpath stroke='rgba(255, 255, 255, 1)' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}
</style>
