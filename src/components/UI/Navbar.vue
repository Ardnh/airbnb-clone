<template>
  <nav class="bg-opacity-0 w-full h-18 flex flex-wrap content-center px-20 py-10 fixed z-10">
    <!-- Airbnb logo -->
      <button class="w-28">
        <airbnb-logo fillColor="#ffffff"></airbnb-logo>
      </button>
      <!-- Primary Navbar items -->
      <div class="flex flex-wrap mx-auto content-center">
        <router-link to="/" class="font-medium text-white px-4">Tempat menginap</router-link>
        <router-link to="/" class="font-medium text-white px-4">Pengalaman</router-link>
        <router-link to="/" class="font-medium text-white px-4">Pengalaman Online</router-link>
      </div>
      <!-- Side right items -->
      <div class="flex flex-wrap ml-auto content-center">
        <button class="font-medium text-white" @click="() => router.push('/')">Mulai menerima tamu</button>
        <button @click="() => router.push('/')" class="w-6 mx-4" >
          <network-icon fillColor="#ffffff"></network-icon>
        </button>
        <button @click="() => router.push('/')" class="bg-white flex flex-wrap content-center rounded-full ring-2 p-2 ring-gray-400">
          <div class="w-4">
            <list-icon></list-icon>
          </div>
          <div class="w-4">
            <user-icon></user-icon>
          </div>
        </button>
      </div>
  </nav>
</template>

<script>
import AirbnbLogo from './icon/AirbnbLogo.vue'
import NetworkIcon from './icon/NetworkIcon.vue'
import ListIcon from './icon/ListIcon.vue'
import UserIcon from './icon/UserIcon.vue'
export default {
  name:'navbar',
  components: { AirbnbLogo, NetworkIcon, ListIcon, UserIcon }
}
</script>

<style>

</style>