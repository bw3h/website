<template>
  <header class="app-header">
    <v-header
      logo="images/nio3-logo.png"
   
      :menu-items="menuItems"
    />
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
  data() {
    return {
      headerCta: {
        label: 'Start Building',
        link: process.env.web3heaven_DASHBOARD_URL,
      },
      menuItems: [
        
      {
          name: 'About',
          link: '/about/',
        },
      // {
      //     name: 'Asknio',
      //     link: 'https://asknio.com',
      //     external: true,
      //   },
      {
          name: 'Blog',
          link: 'https://blog.web3heaven.net',
          external: true,
        },
        //     {
        //   name: 'NioDEX',
        //   link: 'https://dex.web3heaven.net',
        //   external: true,
        // },
        {
          name: 'Explorer',
          link: 'https://scan.web3heaven.net',
          external: true,
        },
        
        {
          name: 'Roadmap',
          link: '/tech/',
        },
        {
           name: 'Wallet',
           link: 'https://wallet.web3heaven.net',
           external: true,
         },
        
        {
          name: 'Whitepaper',
          link: 'https://web3heaven.net/whitepaper.pdf',
          external: true,
        },
      ],
    }
  },
}
</script>

<style scoped>
.app-header {
  position: sticky;
  top: 0;
  z-index: 100;
  background-color: #00000096;
}
</style>
