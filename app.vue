<template>
  <div class="bg-gray-100 min-h-screen">
    <!-- Header Section -->
    <header class="bg-white shadow-md">
      <div class="container mx-auto py-6 flex justify-between items-center">
        <h1 class="text-3xl font-bold text-yellow-400">Rafilatus Suhaimah</h1>
        <nav class="space-x-4">
          <a href="#" class="text-gray-700 hover:text-yellow-400">Home</a>
          <a href="#" class="text-gray-700 hover:text-yellow-400">About Me</a>
          <a href="#" class="text-gray-700 hover:text-yellow-400">Services</a>
          <a href="#" class="text-gray-700 hover:text-yellow-400">Projects</a>
          <a href="#" class="text-gray-700 hover:text-yellow-400">Contact</a>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="container mx-auto py-12 text-center">
      <h2 class="text-5xl font-bold text-gray-800">Hi, I am <span class="text-yellow-400">Rafilatus Suhaimah</span></h2>
      <h3 class="text-4xl font-semibold text-blue-600">UI & UX Designer</h3>
      <p class="text-gray-500 mt-4">
        rafilatussuhaimah@gmail.com | 0851-7337-9200
      </p>
      <button class="mt-6 px-8 py-3 bg-yellow-400 text-white font-semibold rounded shadow-lg hover:bg-yellow-500 transition duration-300">
        Get in Touch
      </button>

      <!-- Social Icons -->
      <div class="flex justify-center space-x-6 mt-6">
        <a href="#" class="text-blue-600 hover:text-blue-800">
          <i class="fab fa-linkedin fa-2x"></i>
        </a>
        <a href="#" class="text-blue-400 hover:text-blue-600">
          <i class="fab fa-twitter fa-2x"></i>
        </a>
        <a href="#" class="text-gray-700 hover:text-gray-900">
          <i class="fab fa-github fa-2x"></i>
        </a>
      </div>
    </section>

    <!-- About Me Section -->
    <section class="bg-white py-12">
      <div class="container mx-auto flex items-center space-x-6">
        <div class="w-1/2">
          <img
            src="./assets/css/profil.jpg"
            alt="Profile"
            class="rounded-lg shadow-lg w-60"
          />
        </div>
        <div class="w-1/2">
          <h2 class="text-3xl font-bold text-gray-800">About Me</h2>
          <p class="mt-4 text-gray-500">
            Saya adalah mahasiswa aktif jurusan Teknologi Informasi di Universitas Brawijaya. saya memiliki ketertarikan pada bidang desain menciptakan desain yang elegan dan mudah digunakan.
          </p>

          <!-- Skills Progress Bar -->
          <div class="mt-6">
            <p class="text-gray-800">Website Design</p>
            <div class="w-full bg-gray-200 rounded-full h-2.5 mb-4">
              <div class="bg-yellow-400 h-2.5 rounded-full" style="width: 85%"></div>
            </div>

            <p class="text-gray-800">App Design</p>
            <div class="w-full bg-gray-200 rounded-full h-2.5 mb-4">
              <div class="bg-yellow-400 h-2.5 rounded-full" style="width: 90%"></div>
            </div>

            <p class="text-gray-800">Graphic Design</p>
            <div class="w-full bg-gray-200 rounded-full h-2.5 mb-4">
              <div class="bg-yellow-400 h-2.5 rounded-full" style="width: 95%"></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section class="container mx-auto py-12 text-center">
      <h2 class="text-4xl font-bold text-gray-800">Services</h2>
      <p class="text-gray-500 mt-4">
        Saya dapat membuat berbagai desain untuk untuk mewujudkan ide Anda.
      </p>

      <div class="mt-8 grid grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-lg shadow-md">
          <i class="fas fa-paint-brush text-4xl text-yellow-400"></i>
          <h3 class="text-2xl font-semibold mt-4">UI/UX Design</h3>
          <p class="text-gray-500 mt-2">Creating user-friendly and aesthetically pleasing interfaces.</p>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-md">
          <i class="fas fa-vector-square text-4xl text-yellow-400"></i>
          <h3 class="text-2xl font-semibold mt-4">Graphics Design</h3>
          <p class="text-gray-500 mt-2">Crafting visual content to communicate messages.</p>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-md">
          <i class="fas fa-code text-4xl text-yellow-400"></i>
          <h3 class="text-2xl font-semibold mt-4">Web Design</h3>
          <p class="text-gray-500 mt-2">Designing modern and responsive websites.</p>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-md">
          <i class="fas fa-mobile-alt text-4xl text-yellow-400"></i>
          <h3 class="text-2xl font-semibold mt-4">App Design</h3>
          <p class="text-gray-500 mt-2">Designing intuitive mobile applications.</p>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-md">
          <i class="fas fa-tools text-4xl text-yellow-400"></i>
          <h3 class="text-2xl font-semibold mt-4">Development</h3>
          <p class="text-gray-500 mt-2">Building fully functional web applications.</p>
        </div>

        <div class="bg-white p-6 rounded-lg shadow-md">
          <i class="fas fa-lightbulb text-4xl text-yellow-400"></i>
          <h3 class="text-2xl font-semibold mt-4">Creative Solutions</h3>
          <p class="text-gray-500 mt-2">Bringing innovative design solutions to your problems.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
// No JavaScript needed for this static layout
</script>

<style scoped>
/* Tailwind classes handle the majority of the styling */
</style>
