<template>

  <Layout>

    <div class="bg-white rounded-xl shadow-lg p-8">

      <h1 class="text-4xl font-bold text-blue-700">

        👋 Selamat Datang

      </h1>

      <p class="mt-4 text-gray-600">

        Ini adalah project Praktikum 14 menggunakan
        Vue Router, Layout Component, Slot,
        dan Tailwind CSS.

      </p>

      <button
        class="mt-6 bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-lg transition">

        Mulai Belajar

      </button>

    </div>

  </Layout>

</template>

<script setup>
import Layout from '../components/Layout.vue'
</script>