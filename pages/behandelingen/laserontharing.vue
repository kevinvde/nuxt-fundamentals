<template>
  <div>
    <WebsiteHeader :title="'Over ons'"/>

    <section class="text-grey container mx-auto mt-10">
      <div class="mb-4 leading-loose">

        <h1 class="font-bold text-grey-dark text-3xl font-bold">LASERONTHARING</h1>
        <p class="mb-4">Waar traditionele manieren van ontharing gebaseerd zijn op bruut geweld, het haar wordt
          inclusief haarwortel uitgerukt, is laserontharing een zachte ontharing waarbij de huid nauwelijks geïrriteerd
          raakt. Kies voor de Laser methode als u minder pijn verkiest bij ontharing.</p>

        <h1 class="font-bold text-grey-dark text-3xl font-bold">LASERONTHARING: WERKWIJZE</h1>
        <p class="mb-4">Laserontharing werkt door gebruik te maken van het lichaamseigen melanine dat natuurlijk in het
          haar aanwezig is. De laser stuurt een puls doorheen het haar waarvan de hitte door de melanine naar de
          haarwortel getransporteerd wordt, waardoor de haarwortel wordt vernietigd. Een speciale koeltip die in
          aanraking komt met uw huid zorgt ervoor dat wanneer de laser een zeer korte puls geeft, de omliggende huid en
          onderliggende bloedvaatjes beschermd zijn tegen de hitte van de laser. Het resultaat is een pijnloze
          ontharing. Laserbehandeling geniet daardoor de voorkeur van steeds meer mensen!</p>

        <p class="mb-4">Bovendien zorgt ontharing met de laser na 5 tot 8 behandelingen voor een definitieve ontharing.
          Tachtig tot negentig procent van de behandelde haren is dan definitief weg!</p>

        <h1 class="font-bold text-grey-dark text-3xl font-bold">ONTHARING LASER</h1>
        <p class="mb-4">Het aantal behandelingen dat u nodig heeft, hangt af van de te ontharen plaats op uw lichaam,
          het type van uw huid en de kleur van uw haar. Om dat te bepalen bieden wij u een gratis testsessie
          laserontharing aan. Wij behandelen u met de laser op een oppervlakte van drie vierkante centimeter.
          Afhankelijk van hoe u reageert op deze laserontharing, bepalen wij dan hoeveel keer u onder de laser moet voor
          een definitief resultaat.</p>
      </div>

      <iframe width="500" height="100"
              src="https://www.laserontharing.be/banners/generate.php?lang=nl&s=vrouwen&w=500&h=100&inst_id=566"
              frameborder="0"></iframe>

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
        title: 'Zachte ontharing waarbij de huid nauwelijks geïrriteerd raakt',
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
