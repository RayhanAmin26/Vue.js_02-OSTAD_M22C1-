<script setup>
const country = "Russia"
const capital = "Mwosko"

</script>


<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <h1>Welcome to {{ country }}</h1>
      <p>The capital is {{ capital }} </p>
     
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>

</style>
