<template>
    <div class="min-h-screen bg-gray-100 flex flex-col justify-center items-center text-center">
      <header class="text-2xl font-bold mb-6">
        Expose - Exporteer Operating System Enterprise
      </header>
  
      <section class="text-lg mb-4 px-6">
        Bergabung bersama early adopter yang lain untuk menghadapi revolusi industri.
      </section>
  
      <div class="text-2xl font-bold text-red-600 mb-8">
        Sisa Kuota 93 dari 1000
      </div>
  
      <button 
        @click="register"
        :class="{
          'bg-blue-500 hover:bg-blue-700 text-white': remainingQuota > 0,
          'bg-gray-400 text-gray-200': remainingQuota <= 0
        }"
        class="px-6 py-3 text-lg rounded-md focus:outline-none"
        :disabled="remainingQuota <= 0"
      >
        Register Now
      </button>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  
  const remainingQuota = ref(50);
  
  const register = () => {
    window.location.href = "https://whatsform.com/hhF8Mx"
  };
  </script>
  
  <style scoped>
  /* Tailwind handles most of the styling. No additional styles needed here. */
  </style>
  