<template>
  <main>
    <CareersHeroSection />
    <AboutOurCulture />
    <CareersOpenPositions />
    <CareersEndSection />
  </main>
</template>

<script>
export default {
  layout: 'page',
  head() {
    return {
      title: 'Careers - Luminet',
    }
  },
}
</script>

<style lang="postcss" scoped>
@import url('../components/lib/media-query-helper.css');

main {
  overflow-x: hidden;
  scroll-behavior: smooth;
}

main > * {
  margin-top: 6rem;

  @media (--viewport-medium) {
    margin-top: 4rem;
  }

  @media (--viewport-small) {
    margin-top: 2rem;
  }
}
</style>
