<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>

    <section class="text-grey container mx-auto mt-10">
      <div class="mb-4 leading-loose">
        <p class="mb-4">
          Tegenwoordig willen steeds meer mensen beharing verwijderd hebben. Dat beharing ongewenst is, is afhankelijk
          van een aantal factoren. Het is doorgaans zo dat mannen en vrouwen verschillende opvattingen hebben over het
          ontharen. Vrouwen vinden een gladde, onthaarde huid vaak erg prettig.
        </p>
        <p class="mb-4">
          Daarnaast speelt de locatie van de beharing ook een rol of het al dan niet ongewenst is. Steeds meer mannen
          vinden beharing op de rug, schouders en borst storend. Vrouwen houden beharing in de oksels, bikinilijn en
          benen regelmatig bij met het scheermes. Beharing op de armen wordt als minder storend ervaren.
        </p>
        <p class="mb-4">
          Als een man een beetje rug- en/of borstbeharing heeft, wordt dat meestal niet als vervelend ervaren, maar als
          het aantal haren meer is, dan vaak wel. Ook als de kleur van de beharing donker is, kan dat ook storend zijn.
          Dit geldt ook voor vrouwen. Als de beharing op de benen of op andere plekken minder omvangrijk is en ook licht
          van kleur, storen vrouwen zich minder snel hieraan, dan wanneer er sprake is van dikke en donkere beharing.
        </p>

        <p class="mb-4">
          Door het harsen, scheren en/of epileren, kunnen er ingegroeide haren, ontstekingen of irritaties ontstaan.
          Laat u daarom professioneel bijstaan.
        </p>
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
          <p class="uppercase font-bold text-grey-dark">Wenkbrauw / bovenlip</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 8</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Gelaat / oksel /bikinilijn</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 12,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Onderbenen</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 17,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Volledige benen</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 30</p>
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
        title: 'Ontharing van rug, borst, ...',
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
