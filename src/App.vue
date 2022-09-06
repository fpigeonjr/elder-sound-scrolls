<template>
  <div id="app">
    <header class="container mx-auto max-w-screen-md">
      <div class="mt-4">
        <router-link to="/" exact>
          <h1 class="text-2xl md:text-4xl font-bold mb-3 pl-3">
            The Elder Sound Scrolls
          </h1>
        </router-link>
      </div>
    </header>
    <nav class="py-3 pl-5 md:py-1 mb-4 border-t-2 border-b-2 border-gray-200">
      <div class="container mx-auto max-w-screen-md">
        <router-link to="/" exact>Home</router-link>
        <router-link to="/download" class="ml-10 md:ml-4">Download</router-link>
        <router-link to="/about" class="ml-10 md:ml-4">About</router-link>
      </div>
    </nav>
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
