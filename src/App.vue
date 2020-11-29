<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,400;1,200&display=swap" rel="stylesheet">
    <Revelry />
  </div>
</template>

<script>
import Revelry from "@/components/Revelry";

export default {
  name: 'App',
  components: {
    Revelry
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>
