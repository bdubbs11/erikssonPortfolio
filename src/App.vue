<template>
    <div class="flex flex-col text-white min-h-screen">
      <nav class="flex flex-row justify-between items-center w-screen my-auto px-6 py-4">
        <router-link to="/" class="text-xl md:text-2xl hover:bg-accent rounded-xs p-1 cursor-pointer ease-in-out duration-300">William Eriksson </router-link>
        <div class="flex gap-10 text-base md:text-xl mr-2 md:mr-6">
          <router-link to="/projects" class="mr-1 md:mr-6 hover:bg-accent rounded-xs p-1 cursor-pointer ease-in-out duration-300">Projects </router-link>
          <router-link to="/about" class="hover:bg-accent rounded-xs p-1 cursor-pointer ease-in-out duration-300">About</router-link>
        </div>

      </nav>

      <main class="text-center text-white flex-1">
        <router-view />
        <slot></slot>
      </main>
    </div>

    <footer class="text-center text-gray-500 text-xs p-4">
      <p>William Eriksson Project Coordinator Personal Website</p>
    </footer>
</template>
