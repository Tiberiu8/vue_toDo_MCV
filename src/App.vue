<script>
export default {
  name: "App",
  components: {},
};
</script>
<template>
  <main class="main-wrapper">
    <h1 class="page-title">ToDo MCV</h1>
    <p class="subtitle">A todo app powered by Vue 3 + Vite</p>
    <input type="text" />
    <button>Add</button>
  </main>
</template>

<style>
html {
  background-color: #4650dd;
}
.main-wrapper {
  max-width: 600px;
  margin: 0 auto;
}
.page-title {
  font-size: 44px;
  letter-spacing: 1.8.px;
  color: #000000;
  margin-bottom: 0px;
  margin-top: 104px;
}
.subtitle {
  font-size: 1rem;
  font-weight: bold;
  color: #000000;
  margin-top: 0;
}
</style>
