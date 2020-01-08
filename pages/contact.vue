<template>
  <div>
    <section class="text-grey container mx-auto mt-8 mb-4">
      <div class="flex content-start flex-wrap mb-4 px-4">
        <div class="w-1/1 lg:w-2/3 pr-12 pb-4">
          <h1 class="font-bold mb-4 text-grey-dark text-3xl">Neem contact op</h1>
          <input id="name" class="block focus:outline-none border-b-2 px-4 py-2 mb-6 w-full" type="text"
                 placeholder="Naam"/>
          <input id="email" class="block focus:outline-none border-b-2 px-4 py-2 mb-6 w-full" type="text"
                 placeholder="Email"/>
          <input id="subject" class="block focus:outline-none border-b-2 px-4 py-2 mb-6 w-full" type="text"
                 placeholder="Onderwerp"/>
          <textarea id="body" class="block focus:outline-none border-b-2 px-4 py-2 mb-6 w-full" rows="10"
                    placeholder="Bericht"></textarea>
          <button onclick="sendMail()"><span
            class="inline-block bg-pink rounded-lg px-8 py-3 text-sm font-semibold text-white">Verstuur</span></button>
        </div>
        <div class="w-1/1 lg:w-1/3">
          <h1 class="font-bold mb-4 text-grey-dark text-3xl">Openingsuren</h1>

          <div class="flex content-start flex-wrap mb-4">
            <div class="w-1/2 my-1">Maandag</div>
            <div class="w-1/2 my-1">18:30 - 21:00 uur</div>
            <div class="w-1/2 my-1">Dinsdag</div>
            <div class="w-1/2 my-1">Gesloten</div>
            <div class="w-1/2 my-1">Woensdag</div>
            <div class="w-1/2 my-1">9:00 - 11:15 uur</div>
            <div class="w-1/2 my-1">Donderdag</div>
            <div class="w-1/2 my-1">9:00 - 21:00 uur</div>
            <div class="w-1/2 my-1">Vrijdag</div>
            <div class="w-1/2 my-1">9:00 - 17:00 uur</div>
            <div class="w-1/2 my-1">Zaterdag</div>
            <div class="w-1/2 my-1">9:00 - 14:00 uur</div>
            <div class="w-1/2 my-1">Zondag</div>
            <div class="w-1/2 my-1">Gesloten</div>
          </div>

          <div class="bg-pink w-full text-white rounded-lg p-8">
            <div class="flex">
              <div class="w-6">
                <i class="fas fa-map-marker-alt"></i>
              </div>
              <div class="w-8/9">
                <p class="text-lg">Locatie</p>
                <p>Bombardonstraat 182, 1770 Liedekerke</p>
              </div>
            </div>

            <div class="flex pt-4">
              <div class="w-6">
                <i class="far fa-paper-plane"></i>
              </div>
              <div class="w-8/9">
                <p class="text-lg">Mail ons</p>
                <p><a class="text-white" href="mailto:excliesa@telenet.be">excliesa@telenet.be</a></p>
              </div>
            </div>

            <div class="flex pt-4">
              <div class="w-6">
                <i class="fas fa-mobile-alt"></i>
              </div>
              <div class="w-8/9">
                <p class="text-lg">Bel ons</p>
                <p><a class="text-white no-underline" href="tel:0477208174">0477/20.81.74</a></p>
              </div>
            </div>
          </div>
        </div>
      </div>


    </section>

    <section class="mt-6">
      <iframe class="w-full h-80" frameborder="0" style="border:0"
              src="https://www.google.com/maps/embed/v1/place?key=AIzaSyALn6FM45dfUOUiDwCwA_q586rM2ifWrxI&q=Excliesa"
              allowfullscreen>
      </iframe>

    </section>

    <WebsiteFooter/>
  </div>
</template>

<script>
  import WebsiteFooter from "../components/WebsiteFooter";

  export default {
    components: {WebsiteFooter},
    head() {
      return {
        title: 'Contacteer ons voor meer informatie',
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

<style scoped>

</style>
