<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>
    <section class="text-grey container mx-auto mt-8">
      <div class="flex flex-wrap flex-col sm:flex-col md:flex-row lg:flex-row xl:flex-row">
        <div v-for="behandeling in behandelingen" class="sm:w-full md:w-1/2 lg:w-1/3 px-4 py-4">
          <div class="max-w-md overflow-hidden shadow">
            <img class="w-full h-64 object-cover" :src="behandeling.image">
            <div class="px-6 py-4 h-48">
              <div class="text-2xl mb-2 text-grey-dark text-center mb-4">{{behandeling.title}}</div>
              <p class="text-grey text-center leading-loose">
                {{behandeling.description}}
              </p>
            </div>
            <div class="text-center px-6 py-4">
              <nuxt-link :to="{name: behandeling.link}"><span
                class="inline-block bg-pink rounded-full px-3 py-1 text-sm font-semibold text-white mr-2">LEES MEER</span>
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </section>
    <WebsiteFooter />
  </div>
</template>

<script>

  import WebsiteFooter from "../../components/WebsiteFooter";
  import WebsiteHeader from "../../components/WebsiteHeader";

  export default {
    components: {
      WebsiteFooter,
      WebsiteHeader
    },
    computed: {
      behandelingen () {
        return this.$store.state.behandelingen.all;
      }
    },
    head () {
      return {
        title: 'Mironeedling is een zeer efficiënte manier voor acné-littekens, fijne lijntjes & rimpels, grove poriën en huidversteviging.',
        link: [
          {
            rel: 'canonical',
            href: 'https://www.excliesa.be' + this.$route.path,
          }
        ]
      }
    }  }
</script>
