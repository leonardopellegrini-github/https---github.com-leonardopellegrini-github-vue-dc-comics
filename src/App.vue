<template>

  <div>
    <HeaderNuovo />

    <MainNuovo />

    <FooterNuovo />
  </div>
   
</template>

<script>
import HeaderNuovo from '@/components/Header.vue'
import FooterNuovo from '@/components/Footer.vue'
import MainNuovo from '@/components/Main.vue'

export default {
  name: 'App',
  components: {
    HeaderNuovo,
    FooterNuovo,
    MainNuovo
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500&display=swap');
*{
  font-family: 'Open Sans', sans-serif;
}

</style>
