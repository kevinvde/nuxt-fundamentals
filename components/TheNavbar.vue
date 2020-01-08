<template>
  <div class="bg-grey-darker">
    <nav class="flex items-center justify-between flex-wrap bg-teal p-6 container mx-auto">
      <div class="flex items-center flex-no-shrink text-white mr-6">
        <div>
          <p class="text-4xl">EXCLIESA</p>
          <p class="text-xs -mt-3">Nails, Spa, Beauty & Personal Care</p>
        </div>
      </div>
      <div id="menuToggle" class="block lg:hidden">
        <button class="flex items-center px-3 py-2 border rounded text-white ">
          <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
        </button>
      </div>
      <div id="menu" class="w-full block hidden sm:hidden md:hidden lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow">
          <nuxt-link :to="{name: 'index'}"  class="pr-6 lg:border-r-2 block mt-4 lg:inline-block lg:mt-0 text-white no-underline hover:text-white mr-4">
            HOME
          </nuxt-link>
          <nuxt-link :to="{name: 'behandelingen'}" class="pr-6 lg:border-r-2 block mt-4 lg:inline-block lg:mt-0 text-white no-underline hover:text-white mr-4">
            BEHANDELINGEN
          </nuxt-link>
          <nuxt-link :to="{name: 'gallerij'}" class="pr-6 lg:border-r-2 block mt-4 lg:inline-block lg:mt-0 text-white no-underline hover:text-white mr-4">
            GALLERIJ
          </nuxt-link>
          <nuxt-link :to="{name: 'contact'}" class="pr-6 block mt-4 lg:inline-block lg:mt-0 text-white no-underline hover:text-white">
            CONTACT
          </nuxt-link>
          <a href="https://client.esthios.be/online_booking.html?/6445/nl" target="_blank" class="block mt-4 lg:inline-block lg:mt-0 text-white no-underline hover:text-white">
            <p class="font-bold text-grey"><span
              class="inline-block rounded-full px-3 py-1 text-xs font-semibold text-white bg-pink font-base">AFSPRAAK MAKEN</span>
            </p>
          </a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
  export default {}
</script>
