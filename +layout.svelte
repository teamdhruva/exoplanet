<script>
  export let title = "Exoplanet Data Analysis";
  import "../app.css";
</script>

<div class="min-h-screen bg-neutral-800 text-white flex flex-col">
  <header class="p-4 bg-gradient-to-r from-purple-400 via-pink-500 to-red-500">
    <h1 class="text-3xl font-bold">{title}</h1>
  </header>

  <main class="flex-grow flex flex-col items-center p-4">
    <slot />
  </main>

  <footer class="p-4 bg-neutral-900 text-center">
    <p>&copy; 2024 Team Dhruva. All rights reserved.</p>
  </footer>
</div>

