<template>
  <v-overlay>
    <iframe
      src="https://www.youtube.com/embed/i4PaiLBsy7o"
      title="What is web3heaven? Mission | Benefits | Use Cases"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
      class="absolute-center youtube-embed"
    ></iframe>
    <img
      src="@/assets/icons/close-white.svg"
      class="cursor-pointer position-absolute close-icon"
      title="Close Video"
      @click.stop="$emit('close')"
    />
  </v-overlay>
</template>

<script>
export default {
  name: 'IntroVideo',
  emits: ['close'],
}
</script>

<style scoped lang="postcss">
@import url('../lib/media-query-helper.css');

.youtube-embed {
  width: 64rem;
  height: calc(64rem / 1.77);

  @media (--viewport-medium) {
    width: 96vw;
    height: calc(96vw / 1.77);
  }
}

.close-icon {
  top: 2rem;
  right: 2rem;
  padding: 0.5rem;
}
</style>
