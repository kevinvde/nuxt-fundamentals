<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>
    <section class="text-grey container mx-auto mt-10">
      <div class="mb-4 flex flex-col sm:flex-col md:flex-row lg:flex-row xl:flex-row px-3">
        <div class="sm:w-full md:w-2/5 lg:w-2/5 xl:w-2/5 pb-4 md:pr-4">
          <p class="text-grey-dark text-2xl lg:text-4xl text-center font-semibold">
            Uw garantie voor perfecte nagels, dit zowel voor gel, gelish of acrylnagels, met of zonder verlenging,
            fantasie of naturel.
          </p>
        </div>
        <div class="sm:w-full md:w-3/5 lg:w-3/5 xl:w-3/5 text-grey">
          <div class="flex flex-col sm:flex-col md:flex-row lg:flex-row xl:flex-row">
            <div class="sm:w-full md:w-1/2 lg:w-1/2 xl:w-1/2 md:pr-4">
              <p>Bij ons kan u niet enkel terecht voor manicure en pedicure, maar tevens ook voor
                gelaatsverzorging &
                massages, en dit in een relaxerend kader waar u kan ontsnappen aan de dagelijkse stress.</p>
            </div>
            <div class="sm:w-full md:w-1/2 lg:w-1/2 xl:w-1/2">
              <p>Sinds de oudheid is geweten dat er een balans is tussen geest en lichaam, of anders gezegd "mens
                sana in
                corpore sano", daarom schenken wij ook veel belang u een welbehagen gevoel te mogen
                bezorgen.</p>
              <p class="mt-4">
                Overtuig uzelf en laat u onderdompelen in een oase van rust en sereniteit.
              </p>
            </div>
          </div>


        </div>
      </div>
    </section>
    <section class="container mx-auto my-9">
      <h2 class="font-bold text-2xl text-grey-dark mb-9 text-center">Onze beste promoties</h2>

      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Zen Arragement</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 60</p>
        </div>
        <div class="flex justify-between mt-2">
          <p class="text-grey">Gelaatsverzorging + pedicure</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Voedende gelaatsverzorging
          </p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 42,50</p>
        </div>
        <div class="flex justify-between mt-2">
          <p class="text-grey">reiniging, peeling, epilatie + verwijderen comedonen, massage & voedend masker</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Lash lift</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 50</p>
        </div>
      </div>
    </section>

    <WebsiteFooter/>
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
    head() {
      return {
        title: 'Excliesa: Nails, Spa, Beauty & Personal Care',
        description: 'Vind je dat jouw nagels wel wat extra aandacht verdienen? Kom dan langs bij excliesa Nails & Beauty aan de Bombardonstraat in Liedekerke. Je kunt hier terecht voor mooie verzorgde nagels. Of je nou voor een neutrale kleur gaat of een feestelijke look, het kan allemaal. Daarnaast ben je hier ook aan het juiste adres voor een fijne gelaatsverzorging, manicure, pedicure, verschillende massages, wimperextensions en een goede ontharingsbeurt. Laat je dus volledig onder handen nemen en je zult het salon na een bezoek weer helemaal verzorgd verlaten.',
        keywords: 'nails, nagels, spa, verzorging, beauty, excliesa, gelaatsverzoring, pedicure, massage, wimperextension, ontharing',
        'google-site-verification': '-gf4z58TcbCcPpIY87LYOWEl_MKtwWOA1IOx4Z-Y96s',
        link: [
          {
            rel: 'canonical',
            href: 'https://www.excliesa.be' + this.$route.path,
          }
        ]
      }
    },
    computed: {
      posts() {
        return this.$store.state.posts.all
      }
    }
  }
</script>
