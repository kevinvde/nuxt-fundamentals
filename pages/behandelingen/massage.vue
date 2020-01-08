<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>

    <section class="text-grey container mx-auto mt-10">
      <div class="mb-4 leading-loose">
        <div>
          <h1 class="font-bold text-grey-dark font-bold text-3xl">Relaxerende massages</h1>
          <p class="mb-4">
            De aanraking is 1 van de eerste zintuigen die zich ontwikkelt bij het begin van het leven.
            De relaxerende massage met essentiële oliën is een verzorging die subtiele geuren en zacht vloeiende en
            glijdende bewegingen aaneenschakelt om een diepe ontspanning te bekomen.
          </p>
          <p class="mb-4">
            De breedvloeiende bewegingen, drukkingen en knedingen leiden u weg uit de beknellingen van de dagelijkse
            sleur.
            De natuurlijke plantengeuren brengen rust en scheppen een gevoel van eenheid; lichaam en ziel en de wereld,
            alles in perfecte harmonie.
          </p>

        </div>
      </div>


    </section>
    <section class="text-grey container mx-auto mt-4 mb-9">
      <div>
        <h1 class="font-bold text-grey-dark inline-block text-3xl font-bold">Prijzen</h1>
        <a href="https://client.esthios.be/online_booking.html?/6445/nl" target="_blank"
           class="align-text-bottom inline-block text-white no-underline">
          <p class="font-bold text-grey"><span
            class="inline-block rounded-full px-3 py-1 text-xs font-semibold text-white bg-pink font-base">AFSPRAAK MAKEN</span>
          </p>
        </a>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Relaxerende massage</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">vanaf € 30</p>
        </div>
      </div>

    </section>

    <WebsiteFooter/>
  </div>
</template>
<script>
  import WebsiteFooter from "../../components/WebsiteFooter";
  import WebsiteHeader from "../../components/WebsiteHeader";

  export default {
    components: {WebsiteHeader, WebsiteFooter},
    head () {
      return {
        title: 'Kom genieten van de verschillende massages',
        link: [
          {
            rel: 'canonical',
            href: 'https://www.excliesa.be' + this.$route.path,
          }
        ]
      }
    }
  }
</script>
