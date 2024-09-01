<script setup></script>

<template>
  <div class="flex h-screen bg-[#0e1015]">
    <!-- Colonne de gauche fixe -->
    <div
      class="w-1/3 text-white bg-[#13151b] p-10 pt-40 flex flex-col items-center"
    >
      <img
        src="/public/images/idcard.png"
        alt="Photo de Profil"
        class="w-52 h-52 rounded mb-4 object-cover"
      />
      <h1 class="text-xl font-bold mb-4">Nom Prénom</h1>
      <ul class="space-y-2">
        <li>
          <button
            class="w-full text-left text-[#5bc8d2] hover:text-[#5bc8d2] focus:outline-none"
            @click="currentSection.value = 'about'"
          >
            À propos
          </button>
        </li>
        <li>
          <button
            class="w-full text-left text-[#5bc8d2] hover:text-[#5bc8d2] focus:outline-none"
            @click="currentSection.value = 'skills'"
          >
            Compétences
          </button>
        </li>
        <li>
          <button
            class="w-full text-left text-[#5bc8d2] hover:text-[#5bc8d2] focus:outline-none"
            @click="currentSection.value = 'experience'"
          >
            Expérience
          </button>
        </li>
        <!-- Ajouter d'autres liens ici -->
      </ul>
    </div>

    <!-- Colonne de droite dynamique -->
    <div class="w-3/4 p-6">
      <component :is="currentSectionComponent"></component>
    </div>
  </div>
</template>
