<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>

    <section class="text-grey container mx-auto mt-10">
      <div class="flex mb-4 leading-loose">
        <div>
          <p class="mb-4">
            De nieuwste evolutie op beauty-vlak heet BB Glow. Bij deze variatie op microneedling worden speciale serums
            in de huid aangebracht. We gebruiken hiervoor een microneedling pen met nano-naaldjes. Hierdoor krijgt de
            huid een
            egale en frisse teint. Acne littekens, couperose, pigmentvlekken,… worden gecamoufleerd. Je kan het
            vergelijken met het aanbrengen van een BB- crème, waarbij het resultaat blijvend is. Behandeling dient om de
            3 tot 6 maand
            herhaald te worden.
          </p>
          <p>
            Voordelen BB Glow:
          </p>
          <ul class="flex flex-wrap">
            <li class="align-baseline pb-2 w-full md:w-1/2">
              <svg class="inline-block h-6 w-6 mr-2 flex-shrink-0" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <circle class="text-pink-100 fill-current" cx="12" cy="12" r="10"></circle>
                <path class="text-pink fill-current"
                      d="M10 14.59l6.3-6.3a1 1 0 0 1 1.4 1.42l-7 7a1 1 0 0 1-1.4 0l-3-3a1 1 0 0 1 1.4-1.42l2.3 2.3z"></path>
              </svg>
              Rimpels: verwijdert fijne rimpeltjes en geeft meer volume aan de huid
            </li>
            <li class="align-baseline pb-2 w-full md:w-1/2">
              <svg class="inline-block h-6 w-6 mr-2 flex-shrink-0" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <circle class="text-pink-100 fill-current" cx="12" cy="12" r="10"></circle>
                <path class="text-pink fill-current"
                      d="M10 14.59l6.3-6.3a1 1 0 0 1 1.4 1.42l-7 7a1 1 0 0 1-1.4 0l-3-3a1 1 0 0 1 1.4-1.42l2.3 2.3z"></path>
              </svg>
              Teint: maakt de huid stralender en egaler
            </li>
            <li class="align-baseline pb-2 w-full md:w-1/2">
              <svg class="inline-block h-6 w-6 mr-2 flex-shrink-0" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <circle class="text-pink-100 fill-current" cx="12" cy="12" r="10"></circle>
                <path class="text-pink fill-current"
                      d="M10 14.59l6.3-6.3a1 1 0 0 1 1.4 1.42l-7 7a1 1 0 0 1-1.4 0l-3-3a1 1 0 0 1 1.4-1.42l2.3 2.3z"></path>
              </svg>
              Vlekken: vermindert ophoping van melanine waardoor vlekken verdwijnen
            </li>
            <li class="align-baseline pb-2 w-full md:w-1/2">
              <svg class="inline-block h-6 w-6 mr-2 flex-shrink-0" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <circle class="text-pink-100 fill-current" cx="12" cy="12" r="10"></circle>
                <path class="text-pink fill-current"
                      d="M10 14.59l6.3-6.3a1 1 0 0 1 1.4 1.42l-7 7a1 1 0 0 1-1.4 0l-3-3a1 1 0 0 1 1.4-1.42l2.3 2.3z"></path>
              </svg>
              Hydratatie: verzacht en hydrateert de huid
            </li>
            <li class="align-baseline pb-2 w-full md:w-1/2">
              <svg class="inline-block h-6 w-6 mr-2 flex-shrink-0" viewBox="0 0 24 24"
                   xmlns="http://www.w3.org/2000/svg">
                <circle class="text-pink-100 fill-current" cx="12" cy="12" r="10"></circle>
                <path class="text-pink fill-current"
                      d="M10 14.59l6.3-6.3a1 1 0 0 1 1.4 1.42l-7 7a1 1 0 0 1-1.4 0l-3-3a1 1 0 0 1 1.4-1.42l2.3 2.3z"></path>
              </svg>
              Poriën: vermindert grove poriën
            </li>
          </ul>
        </div>
      </div>


    </section>
    <section class="text-grey container mx-auto mt-4 mb-9">
      <div>
        <h1 class="font-bold text-grey-dark inline-block text-3xl font-bold">Prijzen</h1>
        <a class="align-text-bottom inline-block text-white no-underline"
           href="https://client.esthios.be/online_booking.html?/6445/nl" target="_blank">
          <p class="font-bold text-grey"><span
            class="inline-block rounded-full px-3 py-1 text-xs font-semibold text-white bg-pink font-base">AFSPRAAK MAKEN</span>
          </p>
        </a>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">1 sessie</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 125</p>
        </div>
      </div>
      <div class="p-4 flex flex-col justify-between leading-normal mt-4">
        <div class="flex justify-between">
          <p class="uppercase font-bold text-grey-dark">3 sessies</p>
          <div class="border-b-2 border-grey-light flex-grow border-dotted mx-2 mb-2"></div>
          <p class="font-bold text-grey-dark">€ 300</p>
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
        title: 'De nieuwste evolutie op beauty-vlak heet BB Glow.',
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
