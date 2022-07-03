<script setup>
import Aplayer from "vue-aplayer"
import albumCover from "../assets/album-cover.jpg"
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
    title: "Orion the Artist feat. MZ – Meditate to Gem Remix",
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
  <div>
    <img :src="albumCover" alt="album cover" class="rounded-md" />
    <Aplayer
      :music="{
        title: 'Composer Producer DJ Elder (Skit)',
        artist: 'The Elder Sounds Scrolls',
        src: '/Composer Producer DJ Elder.mp3',
        pic: '/album-cover.jpg',
        theme: '#e5b24b'
      }"
      :list="album"
    />
  </div>
</template>
