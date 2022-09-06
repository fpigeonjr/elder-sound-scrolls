<script setup>
const album = [
  {
    title: "Sivion – I'm Good Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Sivion ImGoodRemix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Cross Movement – House of Reps Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Cross Movement HouseofReps Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Shai Linne feat. TImothy Brindle – Mercy and Grace Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Shai Linne Brindle MercyandGrace Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Orion TheArtist feat. MZ – Meditate to Gem Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Orion MZ MeditateToGem Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Absent Minded – Two Guitars",
    artist: "The Elder Sounds Scrolls",
    src: "/Absent Minded TwoGuitars.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Die Rek – HalleluYah Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/DieRek HalleluYah Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Mr. Pickney – Peculiar Creatures Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Mr Pickney Peculiar People Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Jeremiah Dirt – Times So Hard Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/JeremiahDirt Timessohard Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "D Rock – In the Mix Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/DRock IntheMix .mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "James Gardin – Soul Rich Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/James Gardin SoulRichRemix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "La Symphony – San Diego Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/La Symphony SanDiego Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  }
]
</script>

<template>
  <div class="overflow-x-auto relative shadow-md sm:rounded-lg mt-8">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
      <thead
        class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400"
      >
        <tr>
          <th scope="col" class="py-3 px-6">Title</th>
          <th scope="col" class="py-3 px-6">Album</th>
          <th scope="col" class="py-3 px-6">Download</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="track in album" :key="track.title" class="bg-white border-b">
          <th
            scope="row"
            class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap"
          >
            {{ track.title }}
          </th>
          <td class="py-4 px-6">{{ track.artist }}</td>
          <td class="py-4 px-6">
            <a
              :href="track.src"
              class="font-medium text-blue-600 hover:underline"
              >Download</a
            >
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>
