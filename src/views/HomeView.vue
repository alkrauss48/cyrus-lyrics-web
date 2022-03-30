<template>
  <div class="home">
    <img class="logo" alt="CyrusLyrics logo" src="../assets/logo.jpeg">
    <h1>Welcome to CyrusLyrics!</h1>
    <div>
      <a
        class="app-store-link"
        target="_blank"
        href="https://apps.apple.com/us/app/cyruslyrics/id1613010334"
      >
        <img
          class="app-store-image"
          alt="Download CyrusLyrics on the App Store"
          src="../assets/download-on-the-app-store.svg"
        />
      </a>
    </div>
    <p>
      CyrusLyrics is an iOS app to help you quickly store, find, and add the
      lyrics of songs that you like to sing.
    </p>
    <p>Watch the following YouTube video to learn about how to use the app.</p>
    <div class="yt-video">
      <iframe
        width="560"
        height="820"
        src="https://www.youtube.com/embed/videoseries?list=PLWXp2X5PBDOmFd1kqyYsPtYwdgXIfDZT3"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>

  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
// import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
  components: {
    // HelloWorld
  }
})
</script>

<style scoped lang="scss">
.logo {
  max-width: 10em;
}

.app-store-link {
  display: inline-block;
}

.yt-video {
  margin: 2em 0;

  iframe {
    max-width: 100%;
  }
}
</style>
