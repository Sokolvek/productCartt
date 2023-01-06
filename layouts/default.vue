<template>
  <div id="app">
    <Header/>
    <Nuxt/>
    <!-- <Footer/> -->
  </div>
</template>

<script>
import Header from '@/components/layouts/Header.vue';
import Footer from '@/components/layouts/Footer.vue';

import '../assets/styles/reset.scss'
import '../components/layouts/header.scss'
import '../pages/index.scss'

export default {
  components: {
    Header,
    Footer
  },
 

}
</script>
