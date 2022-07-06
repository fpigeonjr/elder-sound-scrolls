<script setup>
import patrickImg from "@/assets/patrick.jpeg"
</script>

<template>
  <div class="px-3 md:px-0">
    <div class="md:grid md:grid-cols-2 md:gap-8">
      <div>
        <img
          :src="patrickImg"
          alt="DJ ELder at a ball game"
          class="rounded-lg w-full"
        />
      </div>
      <div>
        <h2 class="text-lg md:text-3xl font-bold mb-2">About DJ Elder</h2>
        <div class="space-y-5 text-lg">
          <p>
            DJ Elder is a veteran of the Christian hip hop scene. For this
            project, he was looking for acapellas where he could remix these
            songs using his original beats.
          </p>
          <p>
            The result is a boom bap hip hop album featuring various artists.
          </p>
          <p>
            The beats were made with the legendary E-MU SP-1200, MPC 60ii and
            the Isla S2400.
          </p>
          <h2 class="text-lg md:text-2xl font-bold">Contact</h2>
          <p>
            <span class="font-bold">email: </span>
            <a
              class="text-blue-500 hover:text-blue-800"
              href="mailto:reactivate2@yahoo.com"
              >reactivate2@yahoo.com</a
            >
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
