<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>
    <section class="text-grey container mx-auto mt-10">
      <div class="mb-4 leading-loose">
        <p class="mb-4">Laat jezelf eens verwennen met een van onze arrangementen met een mix van gelaatsverzorging,
          rugmassage, pedicure, manicure en dit telkens vergezeld van lekkere versnapperingen, want niet enkel voor de
          man geldt : 'liefde gaat door de maag'. Deze arrangementen kunnen ook in duo worden gegeven.</p>
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
          <p class="uppercase font-bold text-grey-dark">Gelaatsverzorging – rugmassage – versnappering</p>
          <p class="font-bold text-grey"><span
            class="inline-block rounded-full ml-2 px-3 py-1 text-xs font-semibold text-white bg-pink">2 uur</span>
          </p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 70</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Gelaatsverzorging – rugmassage – pedicure – versnappering</p>
          <p class="font-bold text-grey"><span
            class="inline-block rounded-full ml-2 px-3 py-1 text-xs font-semibold text-white bg-pink">3 uur</span>
          </p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 90</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Gelaatsverzorging – rugmassage – pedicure – manicure –
            versnappering</p>
          <p class="font-bold text-grey"><span
            class="inline-block rounded-full ml-2 px-3 py-1 text-xs font-semibold text-white bg-pink">3u30</span>
          </p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 100</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Anti Age Arragement</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 60</p>
        </div>
        <div class="flex justify-between mt-2">
          <p class="text-grey">Gelaatsverzorging + oogmasker</p>
        </div>
      </div>
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
        title: 'Laat jezelf eens verwennen met een van onze arrangementen',
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
