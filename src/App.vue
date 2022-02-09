<script setup></script>

<template>
  <div id="app" class="">
    <header class="container mx-auto max-w-screen-md">
      <div class="mt-4">
        <router-link to="/" exact>
          <h1 class="text-2xl md:text-4xl font-bold mb-3 pl-3">
            The Elder Sound Scrolls
          </h1>
        </router-link>
        <nav
          class="py-3 md:py-1 pl-3 mb-4 border-t-2 border-b-2 border-gray-200 max-w-screen-lg"
        >
          <router-link to="/" exact>Home</router-link>
          <router-link to="/about" class="ml-10 md:ml-4">About</router-link>
        </nav>
      </div>
    </header>
    <main class="container mx-auto max-w-screen-md mb-24">
      <router-view />
    </main>
  </div>
</template>

<style>
@import "@/assets/base.css";
.router-link-active {
  color: black;
  font-weight: bold;
  border-bottom: 3px solid #e5b24b;
}
</style>
