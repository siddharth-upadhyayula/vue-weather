<template>
  <div id="app">
    <main> 
      <div class="search-box"> 
        <input type="text" class="search-bar" placeholder="Search..."/>
      </div>
    </main>

  </div>
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      api_key: 'c6619fe5bdbed6c3775c65c8f3279bfa'
  }
}
}

</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main { 
  min-height: 100vh;
  padding: 25px;

  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75)); 
}
</style>
