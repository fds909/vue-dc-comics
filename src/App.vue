<template>
  <div id="app">
    <div class="container">
      <header>
          <LogoComp/>
          <NavbarComp/>
      </header>
    </div>
      <main>
        <div class="container">
          <p>--> Content goes here >--</p>
        </div>
      </main>
      
      <BlueMenuComp>
      </BlueMenuComp>

      <footer>

      </footer>
    
  </div>
</template>

<script>
import LogoComp from './components/LogoComp.vue';
import NavbarComp from './components/NavbarComp.vue';
import BlueMenuComp from './components/BlueMenuComp.vue';

export default {
  name: 'App',
  components: {
    LogoComp,
    NavbarComp,
    BlueMenuComp
  }
}
</script>

<style lang="scss">
  body {
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
  }

  .container {
    width: 75%;
    margin: 0 auto;
  }

  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
    background-color: white;
    color: #1c1c1c;
    font-weight: bold;
    font-size: 14px;
  }

  main {
    color: white;
    background-color: #1c1c1c;
    padding: 40px 0;
  }

  main p {
    font-size: 22px;
    font-weight: bold;
  }
</style>
