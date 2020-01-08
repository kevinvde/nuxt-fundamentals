<template>
  <footer class="bg-grey-darker py-4 mt-6">
    <div class="container mx-auto">
      <div class="py-4 text-center">
        <p class="text-4xl">EXCLIESA</p>
        <p class="text-xs -mt-3">Nails, Spa, Beauty & Personal Care</p>
      </div>

      <a class="flex justify-around text-grey" href="https://www.facebook.com/Excliesa-Nails-Beauty-167023220008953/" target="_blank">
        <div class="border-2 border-white rounded-full h-8 w-8 flex items-center justify-center">
          <i class="fab fa-facebook-f"></i>
        </div>
      </a>

      <div class="w-full bg-grey h-px mt-6 "></div>
      <div class="flex justify-between container mx-auto text-grey mt-1">
        <p class="w-1/3 text-left">© Copyright 2019</p>
        <div class="w-1/3 text-center">Icons by <a class="text-grey underline" href="https://www.flaticon.com/packs/massage-and-spa" title="smalllikeart">smalllikeart</a></div>
        <p class="w-1/3 text-right">Gemaakt door Van Den Elshout IT</p>
      </div>
    </div>
  </footer>
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
