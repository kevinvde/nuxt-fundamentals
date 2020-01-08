<template>
  <div>
    <WebsiteHeader :title="'Over ons'" />

    <section class="text-grey container mx-auto my-9 mt-6">
      <section class="leading-zero photos">
        <a href="/images/gallery/4.jpg"><img class="w-full h-auto p-1" src="/images/gallery/4.jpg"></a>
        <a href="/images/gallery/1.jpg"><img class="w-full h-auto p-1" src="/images/gallery/1.jpg"></a>
        <a href="/images/gallery/3.jpg"><img class="w-full h-auto p-1" src="/images/gallery/3.jpg"></a>
        <a href="/images/gallery/6.jpg"><img class="w-full h-auto p-1" src="/images/gallery/6.jpg"></a>
      </section>
      <section class="leading-zero photos">
        <a href="/images/gallery/2.jpg"><img class="w-full h-auto p-1" src="/images/gallery/2.jpg"></a>
        <a href="/images/gallery/5.jpg"><img class="w-full h-auto p-1" src="/images/gallery/5.jpg"></a>
        <a href="/images/gallery/7.jpg"><img class="w-full h-auto p-1" src="/images/gallery/7.jpg"></a>
        <a href="/images/gallery/8.jpg"><img class="w-full h-auto p-1" src="/images/gallery/8.jpg"></a>
        <a href="/images/gallery/9.jpg"><img class="w-full h-auto p-1" src="/images/gallery/9.jpg"></a>
      </section>
    </section>

    <WebsiteFooter />
  </div>
</template>

<script>
  import Logo from '~/components/Logo.vue'
  import WebsiteHeader from '~/components/WebsiteHeader.vue'
  import WebsiteFooter from "../components/WebsiteFooter";

  export default {
    components: {
      WebsiteFooter,
      Logo,
      WebsiteHeader
    },
    head () {
      return {
        title: 'Bekijk enkele sfeerbeelden van Excliesa',
        link: [
          {
            rel: 'canonical',
            href: 'https://www.excliesa.be' + this.$route.path,
          }
        ]
      }
    },
    computed: {
      posts () {
        return this.$store.state.posts.all
      }
    }
  }
</script>

<style scoped>
  .photos {
    -webkit-column-count: 2;
    -webkit-column-gap:   0px;
    -moz-column-count:    2;
    -moz-column-gap:      0px;
    column-count:         2;
    column-gap:           0px;
  }
</style>
