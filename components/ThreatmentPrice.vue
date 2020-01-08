<template>
  <div  class="flex flex-col py-4 md:flex-row md:justify-between">
    <div class="flex flex-col flex-grow">
      <div class="flex">
        <p class="uppercase font-bold text-grey-dark align-middle pb-1 inline-block">
          {{item.title}}
          <span v-if="item.type" class="inline-block rounded-full px-1 py-1 font-semibold text-grey border border-grey text-xxs align-middle">{{item.type}}</span>
        </p>
        <div
          class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2 hidden md:inline-block self-center"></div>
      </div>

      <p class="text-grey pb-1">{{item.description}}</p>
    </div>
    <div class="flex flex-row-reverse md:flex-col md:w-20">
      <p class="font-bold text-grey-dark pl-4 md:pl-0 self-center">€ {{item.price}}</p>
      <p class="font-bold text-grey text-center self-center" v-if="item.duration">
        <span class="inline-block rounded-full px-3 py-1 text-xs font-semibold text-white bg-pink">{{item.duration}}</span>
      </p>
    </div>
  </div>

</template>

<script>
    export default {
        props: {
          item: {
            required: true,
            type: Object
          }

        }
    }
</script>

<style scoped>

</style>
