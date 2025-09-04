<script setup>
import { ref } from 'vue'
import SearchInput from './components/SearchInput.vue'
import WeatherCard from './components/WeatherCard.vue'
</script>
<template>
  <main>
    <!-- Date -->
    <div class="text-center mb-6">
      {{
        new Date().toLocaleDateString('en-us', {
          weekday: 'long',
          year: 'numeric',
          month: 'long',
          day: 'numeric',
        })
      }}
    </div>
    <div>
      <!-- Search -->
      <searchinput />
    </div>
  </main>
</template>
