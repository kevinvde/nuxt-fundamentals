<template>
  <div class="h-48 lg:h-80 bg">
    <div class="w-full h-full overlay flex items-center justify-center">
      <h1 class="font-bold text-white text-5xl">{{title}}</h1>
    </div>
  </div>
</template>

<script>
  export default {
    props: {
      title: {
        required: true,
        type: String
      }
    }
  }
</script>
