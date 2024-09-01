<script setup></script>

<template>
  <div class="flex items-center justify-center h-screen bg-[#0e1015] relative">
    <!-- Section de gauche avec le PNJ -->
    <div class="w-1/4 h-full flex items-center justify-end relative">
      <img src="/public/images/home.png" alt="PNJ" class="absolute left-0 transform -translate-x-1/2" />
    </div>

    <!-- Section de droite avec le titre, le paragraphe et les boutons -->
    <div class="w-1/3 p-8">
      <h1 class="text-4xl font-bold text-[#898d94] mb-4"> <span class="text-white">Frontend</span> Developer.</h1>
      <p class="text-lg text-[#898d94] mb-8">
        Je suis Aurore Verwaerde, une développeuse passionné par la création d'expériences web interactives et innovantes.
        Découvrez mes projets et n'hésitez pas à me contacter pour toute collaboration.
      </p>
      <div class="flex space-x-4">
        <button class="bg-[#5bc8d2] text-white px-4 py-2 rounded hover:bg-[#5bc8d2] ">
          Mes Projets
        </button>
        <button class="bg-[#499da6] text-white px-4 py-2 rounded hover:bg-[#499da6]">
          Me Contacter
        </button>
      </div>
    </div>
  </div>
</template>
