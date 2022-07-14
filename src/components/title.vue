<template>
  <div class="container">
    <img src="../assets/gif.gif" alt="Frog gif">
    <h1>
        My first APP with Vue CLI!!
    </h1>
    <img src="../assets/gif.gif" alt="Frog gif">

  </div>
</template>

<script>
export default {
    name: "MainTitle",
}


</script>

<style scoped>

    .container {
        display: flex;
        justify-content: center;
    }

    h1 {
        font-size: 4rem;
        margin: 4rem;
        cursor: pointer;
    }
</style>