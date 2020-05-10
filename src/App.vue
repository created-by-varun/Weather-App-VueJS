<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div>
    </main>
  </div>
</template>

<script>
  export default {
    name: 'app',
    data() {
      return{
        api_key: "62557ea00f49b10c315c3e1ceef794c3",
      }
    }
  }
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: 'montserrat', sans-serif;
}

#app{
  background-image: url('./assets/cold-bg.jpg');
}

</style>