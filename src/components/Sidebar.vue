<template>
  <aside class="w-64 min-h-screen bg-slate-900 text-white">

    <div class="p-6 border-b border-slate-700">

      <h2 class="text-2xl font-bold">
        Dashboard
      </h2>

      <p class="text-slate-400 text-sm">
        Navigation Menu
      </p>

    </div>

    <nav class="p-5">

      <RouterLink
        to="/"
        class="block p-3 rounded-lg hover:bg-blue-600 transition mb-2">

        🏠 Home

      </RouterLink>

      <RouterLink
        to="/about"
        class="block p-3 rounded-lg hover:bg-blue-600 transition mb-2">

        ℹ️ About

      </RouterLink>

      <RouterLink
        to="/contact"
        class="block p-3 rounded-lg hover:bg-blue-600 transition mb-2">

        📞 Contact

      </RouterLink>

      <RouterLink
        to="/dashboard"
        class="block p-3 rounded-lg hover:bg-blue-600 transition">

        📊 Dashboard

      </RouterLink>

    </nav>

  </aside>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>