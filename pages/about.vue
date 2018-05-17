<template>
  <div class="wrapper">
    <div class="a">
      <h1 class="title">About Roger</h1>
    </div>
    <div class="b">
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
      <p class="title">Rabbits</p>
    </div>
    <div class="c">Jake is the footer now</div>


  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
  .wrapper {
    display: grid;
    grid-template-columns: 0.20fr 0.20fr 0.20fr 0.20fr 0.20fr;
    grid-template-rows: 30vh auto 30vh;
    grid-template-areas: 
      "header header header header header"
      ". main main main ."
      "footer footer footer footer footer";
    background: black;
    padding: 10%;
  }

  div {
    background: white;
  }

  .a {
    grid-area: header;
  }
  .b {
    grid-area: main;
  }
  .c {
    grid-area: footer;
  }

</style>