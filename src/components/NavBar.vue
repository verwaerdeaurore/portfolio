<script setup></script>

<template>
  <nav
    class="border-gray-200 bg-[#13151b] dark:bg-gray-800 dark:border-gray-700"
  >
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <a href="#" class="flex items-center space-x-3 rtl:space-x-reverse">
        <img src="/public/images/logo.png" class="h-8" alt="Logo" />
        <span
          class="self-center text-2xl font-semibold whitespace-nowrap text-white dark:text-white"
          >Aurore Verwaerde</span
        >
      </a>

      <div class="hidden w-full md:block md:w-auto" id="navbar-solid-bg">
        <ul
          class="flex flex-col font-medium mt-4 rounded-lg bg-gray-50 md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0 md:bg-transparent dark:bg-gray-800 md:dark:bg-transparent dark:border-gray-700"
        >
          <li>
            <RouterLink
              to="/"
              class="block py-2 px-3 md:p-0 hover:border-b-4 hover: border-cyan-500 rounded-none text-white bg-white  md:bg-transparent md:text-white md:dark:text-white dark:bg-blue-600 md:dark:bg-transparent"
              aria-current="page"
              >accueil</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/about"
              class="block py-2 px-3 md:p-0 hover:text-white text-white  hover:border-b-4 hover: border-cyan-500 rounded-none md:hover:bg-transparent md:border-0  dark:text-white  dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >à propos</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/about"
              class="block py-2 px-3 md:p-0 text-white   hover:text-white hover:border-b-4 hover: border-cyan-500 rounded-none md:hover:bg-transparent md:border-0  dark:text-white  dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >projets</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/about"
              class="block py-2 px-3 md:p-0 text-white  hover:text-white hover:border-b-4 hover: border-cyan-500 rounded-none md:hover:text-white dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >contact</RouterLink
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
