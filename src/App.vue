<template>
  
  <div id="app">
    
    <div class="container">

      <Title />

      <Hero />

    </div>

  </div>

</template>

<script>

  import Title from '@/components/Title.vue'
  import Hero from '@/components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">

  body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  #app {
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .container{
    width: 80%;
    height: 70%;
    text-align: center;
  }

</style>
