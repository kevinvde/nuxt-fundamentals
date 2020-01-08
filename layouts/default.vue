<template>
  <div class="font-source-sans font-normal text-white leading-normal">
    <TheNavbar/>
    <nuxt/>
  </div>
</template>


<script>
  import TheNavbar from "../components/TheNavbar";

  export default {
    components: {
      TheNavbar
    }
  }
</script>
