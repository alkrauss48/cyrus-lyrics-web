<template>
  <div class="about">
    <h1>About CyrusLyrics</h1>
    <p>Hi, I'm
      <a href="https://thecodeboss.dev" target="_blank">Aaron</a>
      - Cyrus' dad, and the developer of CyrusLyrics.
    </p>
    <p>Even since before Cyrus was born, I loved singing to him, and once he hit
    about 2-4 months old, he really responded to that kind of interaction. But I
    noticed that I regularly couldn't think of a big variety of songs to sing to
    him - and even when I did, I wouldn't remember all of the lyrics.</p>
    <p>I thought "this is crazy; I probably know at least a hundred songs and probably most of
    the lyrics to those songs, so why can't I think of them?" That's why
    CyrusLyrics was born. I built the app for myself so that I could easily
    store and find the lyrics to the songs that I liked to sing to my son.</p>
    <p>I knew that I needed the ability to add song lyrics at a whim with
    minimal effort, so I decided to store the data in a simple Google Sheet.
    I needed it to be dropdead easy to add and remove new songs, because every
    day I found myself finding entirely new batches of songs that I wanted to
    add to my list, so I made sure the app just needed an artist and song name,
    and it found the lyrics based on that. I also wanted the ability to play those songs in Spotify, in
    case I either didn't quite know how the songs were sung, or if I just wanted
    to play the song in the background while I sung.</p>
    <p>And to take the app a step further, I wanted to make it useable by other
    people too, so everyone could create their own Google Sheet through the app
    to start adding songs to.
    Maybe you have a kid that you love to sing to, or maybe you just
    like to sing in general, or maybe you're trying to better learn the lyrics
    to some of your favorite songs. Whatever the reason is for you, I hope you
    enjoy CyrusLyrics</p>
    <div>
      <a
        class="app-store-link"
        target="_blank"
        href="https://testflight.apple.com/join/zNuXIF3a"
      >
        <img
          class="app-store-image"
          alt="Download CyrusLyrics on the App Store"
          src="../assets/download-on-the-app-store.svg"
        />
      </a>
    </div>
  </div>
</template>
<style scoped lang="scss">
.about {
  max-width: 60em;
  margin: 0 auto;
  text-align: left;

  p {
    a {
      text-decoration: none;
      font-weight: bold;
      color: #31a1fd;

      &:hover, &:focus {
        color: #2c3e50;
      }
    }
  }
}
</style>
