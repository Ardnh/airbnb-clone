<template>
  <div class="relative">
    <img :src="heroImage" class="bg-cover bg-center w-full object-cover" style="height: 95vh;">
    <div class="absolute">
      hello
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  data(){
    return{
      heroImage: require('../assets/4002277.jpg')
    }
  }
}
</script>
