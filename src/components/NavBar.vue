<script setup></script>

<template>
  <nav
    class="border-gray-200 bg-fuchsia-200 dark:bg-gray-800 dark:border-gray-700"
  >
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <a href="#" class="flex items-center space-x-3 rtl:space-x-reverse">
        <img src="#" class="h-8" alt="Flowbite Logo" />
        <span
          class="self-center text-2xl font-semibold whitespace-nowrap text-pink-950 dark:text-white"
          >nomdusite</span
        >
      </a>

      <div class="hidden w-full md:block md:w-auto" id="navbar-solid-bg">
        <ul
          class="flex flex-col font-medium mt-4 rounded-lg bg-gray-50 md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0 md:bg-transparent dark:bg-gray-800 md:dark:bg-transparent dark:border-gray-700"
        >
          <li>
            <RouterLink
              to="/"
              class="block py-2 px-3 md:p-0 text-pink-950 bg-pink-950 rounded md:bg-transparent md:text-pink-950 md:dark:text-pink-950 dark:bg-blue-600 md:dark:bg-transparent"
              aria-current="page"
              >Home</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/about"
              class="block py-2 px-3 md:p-0 text-pink-950 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >about</RouterLink
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
