<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>

    <section class="text-grey container mx-auto mt-10">
      <div class="flex mb-4 leading-loose">
        <div>
          <p class="mb-4">
            Een manicure is een behandeling van nagels en handen. Door middel van warme handbaden en vochtregulerende
            lotions wordt de huid gekalmeerd en ontspannen. De nagel wordt in een mooie vorm gevijld en de nagelriem
            wordt wat naar achter geduwd. De dode huidcellen van de nagel worden verwijderd. De nagelriem wordt
            bevochtigd met nagelriemolie. Je kan kiezen voor kunstnagels of je natuurlijke nagels lakken.
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
          <p class="uppercase font-bold text-grey-dark">Acryl/gel full op eigen nagel</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 37,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Acryl french op eigen nagel</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 40</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Acryl met verlenging</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 52,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Gellak</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 27,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Verwijderen acryl, gel of gellak</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 20</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Manicure zonder lakken</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 17,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Manicure met lakken</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 22,50</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">Elke behandeling in spa</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">+ € 5</p>
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
        title: 'Laat je verwennen door een handverzorging',
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
