<script setup>
import Header from './components/Header.vue'
import MainScss from './assets/scss/main.scss'
import Main from './components/main.vue'
import HeaderScss from './assets/scss/header.scss'
import Footer from './components/footer.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="You did it!" />
      <Header/>
      <Main/>
      <Footer/>

    </div>
  </header>



</template>

<style scoped>

</style>
