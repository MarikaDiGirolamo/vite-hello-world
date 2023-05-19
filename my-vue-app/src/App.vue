<script>
import AppTitle from './components/AppTitle.vue'
import AppComponent from './components/AppComponent.vue'

export default {
  components: {
    AppTitle,
    AppComponent,
  }
}
</script>

<template>
  <h1>La mia prima app con Vite</h1>

  <AppTitle />
  <AppComponent />
</template>

<style scoped>
/* .logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
} */
</style>
