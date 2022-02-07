<script setup>
import Aplayer from "vue-aplayer"
import albumCover from "../assets/album-cover.jpg"
const album = [
  {
    title: "Halleluyah Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Halleluyah Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "I'm Good Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Im Good Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "In the Mix Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/In the Mix Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Meditate To Gem Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Meditate To Gem Remix MASTER.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Mercy and Grace Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Mercy and Grace Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Peculiar Creatures Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Peculiar Creatures Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Rise and Fall Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Rise and Fall Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Roul Rich Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Roul Rich Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Times so Hard Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Times so Hard Remix.mp3",
    pic: "/album-cover.jpg",
    theme: "#e5b24b"
  },
  {
    title: "Two Guitars Remix",
    artist: "The Elder Sounds Scrolls",
    src: "/Two Guitars.mp3",
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
        title: 'Intro',
        artist: 'The Elder Sounds Scrolls',
        src: '/Composer Producer DJ Elder.mp3',
        pic: '/album-cover.jpg',
        theme: '#e5b24b'
      }"
      :list="album"
    />
  </div>
</template>
