<template>
  <div>
    <v-text font="sans" size="1rem" >
      <a href="/terms/"
              >
    <v-text size="1rem" >Terms</v-text></a
            >
      © {{ currentYear }} Luminet.
    </v-text>
  </div>
</template>

<script>
export default {
  name: 'AppCopyright',
  computed: {
    currentYear() {
      return new Date().getFullYear()
    },
  },
}
</script>

<style lang="css" scoped>
div {
  padding: 1.5rem;
  text-align: center;
  background-color: #00000085;
}
</style>
