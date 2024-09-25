<template>
  <div class="flex flex-col min-h-screen bg-gray-100">
    <!-- Header -->
    <header class="bg-gray-800 text-white py-6">
      <div class="container mx-auto text-center">
        <h1 class="text-4xl font-bold">Syahputra Tirta Wijaya</h1>
        <p class="text-lg">Mahasiswa Fokasi Universitas Brawijaya, Jurusan Teknologi Informasi</p>
      </div>
    </header>

    <!-- Main Content -->
    <main class="flex-grow container mx-auto p-6 grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Sidebar - Profile Photo & Contact Info -->
      <aside class="col-span-1 bg-white shadow-lg rounded-lg p-6">
        <!-- Foto Profil -->
        <div class="flex justify-center mb-4">
          <img 
            src="assets/img/putra.jpg" 
            alt="Foto Syahputra Tirta Wijaya" 
            class="rounded-full border-4 border-gray-800 shadow-lg w-40 h-40 object-cover"
          />
        </div>
        <!-- Kontak Info -->
        <div class="text-center">
          <h2 class="text-2xl font-semibold text-gray-800 mb-2">Kontak</h2>
          <p class="text-gray-600">syahputra@example.com</p>
          <p class="text-gray-600">+62 812 3456 7890</p>
          <p class="text-gray-600">Malang, Indonesia</p>
        </div>
        <!-- Media Sosial -->
<div class="mt-6 text-center">
  <h2 class="text-2xl font-semibold text-gray-800 mb-2">Media Sosial</h2>
  
  <div class="flex flex-col items-center">
    <a href="https://instagram.com/syhptraaaaaaaaa" class="flex items-center mb-2">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram Logo" class="w-6 h-6 mr-2" />
      syhptraaaaaaaaa
    </a>
    
    <a href="https://linkedin.com/in/syhptra" class="flex items-center mb-2">
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn Logo" class="w-6 h-6 mr-2" />
      syhptra
    </a>

    <a href="https://facebook.com/syhptraaa" class="flex items-center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Logo" class="w-6 h-6 mr-2" />
      syhptraaa
    </a>
  </div>
</div>

      </aside>

      <!-- Main CV Details -->
      <section class="col-span-2">
        <!-- Ringkasan -->
        <div class="bg-white shadow-lg rounded-lg p-6 mb-6">
          <h2 class="text-3xl font-semibold text-gray-800 flex items-center">
            <i class="fas fa-user mr-2"></i> Ringkasan
          </h2>
          <p class="mt-2 text-gray-600">
            Mahasiswa Teknologi Informasi dengan pengalaman kerja di bidang industri dan memiliki keahlian dalam berbagai teknologi. Saya memiliki keterampilan komunikasi dan kepemimpinan yang baik serta antusias dalam bekerja dalam tim.
          </p>
        </div>

        <!-- Pengalaman Kerja -->
        <div class="bg-white shadow-lg rounded-lg p-6 mb-6">
          <h2 class="text-3xl font-semibold text-gray-800 flex items-center">
            <i class="fas fa-briefcase mr-2"></i> Pengalaman Kerja
          </h2>
          <ul class="list-disc list-inside mt-2 text-gray-600">
            <li>Penanting di TNI AL</li>
            <li>Karyawan di Toko Bangunan</li>
            <li>Karyawan di Bengkel Motor</li>
          </ul>
        </div>

        <!-- Pendidikan -->
        <div class="bg-white shadow-lg rounded-lg p-6 mb-6">
          <h2 class="text-3xl font-semibold text-gray-800 flex items-center">
            <i class="fas fa-graduation-cap mr-2"></i> Pendidikan
          </h2>
          <ul class="list-disc list-inside mt-2 text-gray-600">
            <li>SMA N 9 Malang (2019 - 2023)</li>
            <li>Universitas Brawijaya (2023 - Sekarang)</li>
          </ul>
        </div>

        <!-- Keahlian -->
        <div class="bg-white shadow-lg rounded-lg p-6 mb-6">
          <h2 class="text-3xl font-semibold text-gray-800 flex items-center">
            <i class="fas fa-tools mr-2"></i> Keahlian
          </h2>
          <p class="mt-2 text-gray-600">
            Komunikatif, Kerja Sama Tim, Disiplin, Dasar-dasar HTML, CSS, JavaScript, PHP, dan Vue.js.
          </p>
        </div>

        <!-- Sertifikasi & Pelatihan -->
        <div class="bg-white shadow-lg rounded-lg p-6 mb-6">
          <h2 class="text-3xl font-semibold text-gray-800 flex items-center">
            <i class="fas fa-certificate mr-2"></i> Sertifikasi & Pelatihan
          </h2>
          <ul class="list-disc list-inside mt-2 text-gray-600">
            <li>Pelatihan Dasar-dasar Pengembangan Web</li>
            <li>Sertifikasi Microsoft Office Specialist (MOS)</li>
          </ul>
        </div>

        <!-- Bahasa yang Dikuasai -->
        <div class="bg-white shadow-lg rounded-lg p-6 mb-6">
          <h2 class="text-3xl font-semibold text-gray-800 flex items-center">
            <i class="fas fa-language mr-2"></i> Bahasa yang Dikuasai
          </h2>
          <p class="mt-2 text-gray-600">
            Bahasa Indonesia, Bahasa Inggris
          </p>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
      <p>&copy; 2024 Syahputra Tirta Wijaya. Semua hak dilindungi.</p>
    </footer>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'CV Syahputra Tirta Wijaya',
      link: [
        { rel: 'stylesheet', href: 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css' }
      ]
    }
  }
}
</script>

<style>
/* Tambahkan CSS kustom jika diperlukan */
</style>
