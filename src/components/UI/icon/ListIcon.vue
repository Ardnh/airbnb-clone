<template>
   <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 12 20">
      <path :fill="fillColor" d="M0 3h20v2H0V3zm0 4h20v2H0V7zm0 4h20v2H0v-2zm0"/>
   </svg>
</template>

<script>
export default {
   name: "list icon",
   props: ['fillColor']

}
</script>

<style>

</style>