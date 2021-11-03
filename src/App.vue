<template>
    <Navbar/>
    <router-view/>
</template>

<script>
// @ is an alias to /src
import Navbar from './components/UI/Navbar'
export default {
  name: 'App',
  components: { Navbar }
}
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');
#app {
  font-family:Roboto, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
