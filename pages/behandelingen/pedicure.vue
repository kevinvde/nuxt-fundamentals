<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>

    <section class="text-grey container mx-auto mt-10">
      <div class="flex mb-4 leading-loose">
        <div>
          <p class="mb-4">
            Een pedicure is een behandeling van nagels en voeten.

            Wacht niet tot klachten je dwingen om stappen te ondernemen,

            zoals bij overtollig eelt, likdoorns, kloven, ingegroeide, verdikte of schimmelnagels,...

            maar geef je voetjes de aandacht die ze verdienen.

            Ons hele lichaam steunt op onze voeten.

            Doen deze pijn kan dit zelfs ongemerkt onze houding veranderen. Daardoor kunnen dan weer rugklachten
            ontstaan.
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
          <p class="uppercase font-bold text-grey-dark">Medische pedicure zonder lakken</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 22,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Medische pedicure met lakken</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 27,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Gelish op tenen (basis pedicure) </p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 27,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Gelish op tenen (medische pedicure)</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 37,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Pedicure aan huis in Liedekerke</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 25</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Pedicure aan huis buiten Liedekerke</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 27,50</p>
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
        title: 'Laat je voeten goed verzorgen',
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
