<template>
  <div class="flex">

    <Sidebar />

    <div class="flex-1">

      <Header />

      <main class="p-6">
        <slot />
      </main>

    </div>

  </div>
</template>

<script setup>
import Header from './Header.vue'
import Sidebar from './Sidebar.vue'
</script>