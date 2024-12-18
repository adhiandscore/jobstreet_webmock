<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Job Posting Page</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50">

  <!-- Header -->
  <header class="bg-white shadow-md py-4">
    <div class="container mx-auto flex justify-between items-center px-4">
      <div class="text-xl font-bold text-blue-700">jobstreet</div>
      <nav>
        <ul class="flex gap-4">
          <li><a href="#" class="text-gray-600 hover:text-blue-600">Cari Lowongan</a></li>
          <li><a href="#" class="text-gray-600 hover:text-blue-600">Lihat Profil</a></li>
          <li><a href="#" class="text-gray-600 hover:text-blue-600">Komunitas</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Section -->
  <main class="container mx-auto p-6 bg-white mt-6 rounded-lg shadow-md">
    <!-- Company Logo -->
    <div class="flex items-center space-x-4 mb-6">
      <img src="https://i.pinimg.com/736x/13/08/43/130843d384f2f4884608f65afcc23a6e.jpg" alt="Radian Logo" class="w-20 h-20">
      <h1 class="text-3xl font-bold text-gray-700">RADIAN</h1>
    </div>

    <!-- Job Details -->
    <section class="mb-6">
      <h2 class="text-2xl font-semibold text-gray-800 mb-2">Junior Developer</h2>
      <p class="text-gray-600 mb-4">PT Radian Solusi Integral</p>
      <ul class="text-gray-600 mb-4">
        <li>📍 Jakarta Selatan, Jakarta Raya</li>
        <li>💼 Developer/Programmer (Teknologi Informasi & Komunikasi)</li>
        <li>⏳ Kontrak</li>
        <li>💰 Rp 6,000,000 - Rp 7,000,000 per bulan</li>
      </ul>
      <p class="text-gray-500 text-sm">Posted 7 hari yang lalu</p>
    </section>

    <!-- Action Buttons -->
    <div class="flex gap-4 mb-8">
      <button class="bg-pink-500 text-white py-2 px-4 rounded hover:bg-pink-600">
        Lamaran Cepat
      </button>
      <button class="bg-gray-200 text-gray-800 py-2 px-4 rounded hover:bg-gray-300">
        Simpan
      </button>
    </div>

    <!-- Skills Section -->
    <div>
      <h3 class="text-gray-700 font-semibold mb-2">Bagaimana Anda cocok</h3>
      <div class="flex flex-wrap gap-2">
        <span class="bg-blue-100 text-blue-800 text-sm px-3 py-1 rounded-full">Pengembangan Software</span>
        <span class="bg-blue-100 text-blue-800 text-sm px-3 py-1 rounded-full">Bahasa Pemrograman</span>
        <span class="bg-blue-100 text-blue-800 text-sm px-3 py-1 rounded-full">Pemrograman PHP</span>
        <span class="bg-blue-100 text-blue-800 text-sm px-3 py-1 rounded-full">Pemrograman HTML</span>
      </div>
    </div>
  </main>

</body>
</html>
