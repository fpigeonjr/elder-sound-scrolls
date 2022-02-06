<script setup>
import Aplayer from "vue-aplayer"
import albumCover from "../assets/album-cover.jpg"
const album = [
  {
    title: "Halleluyah Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Halleluyah Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "I'm Good Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Im Good Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "In the Mix Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/In the Mix Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "Meditate To Gem Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Meditate To Gem Remix MASTER.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "Mercy and Grace Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Mercy and Grace Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "Peculiar Creatures Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Peculiar Creatures Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "Rise and Fall Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Rise and Fall Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "Roul Rich Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Roul Rich Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "Times so Hard Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Times so Hard Remix.mp3",
    pic: "/public/album-cover.jpg"
  },
  {
    title: "Two Guitars Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/public/Two Guitars.mp3",
    pic: "/public/album-cover.jpg"
  }
]
</script>

<template>
  <main>
    <img :src="albumCover" alt="album cover" />
    <Aplayer
      :music="{
        title: 'Intro',
        artist: 'The Elder Sounds Scrolls',
        src: '/public/Composer Producer DJ Elder.mp3',
        pic: '/public/album-cover.jpg'
      }"
      :list="album"
    />
  </main>
</template>
