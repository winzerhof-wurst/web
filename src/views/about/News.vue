<template>
    <Content>
        <h1>Aktuelles</h1>

        <ContentTile>
          <h2>Leserhahn</h2>
          <p>
            An unserem letzten Lesetag wurde heute unser Traminer gelesen. Somit sind alle Trauben im Keller und die Ernte 2021 ist abgeschlossen. Wir freuen uns bereits auf die weiteren Arbeitsschritte im Keller um euch im Frühjahr unsere neuen Weine präsentieren zu können.
          </p>
          <img class="img-fluid"
                     :src="require('../../images/202110_leserhahn.jpg')"
                     alt="Kürbisernte">
        </ContentTile>

        <ContentTile>
          <h2>Wir sind im Salon 2021</h2>
          <p>
            Unser Weinviertel DAC Hochsteiner 2020 hat sich in Österreichs härtestem Weinwettbewerb bewiesen und zählt nun zu den Besten 270 Weinen des Landes. Wir freuen uns riesig über diese Auszeichnung.
          </p>
          <img class="img-fluid"
                     :src="require('../../images/202108_salon.jpg')"
                     alt="Offene Kellertür am Winzerhof Wurst. Vom 12. bis 15. August 2021 verwühnen wir euch in unserem Presshaus mit Wein und hausgemachten Schmankerln.">
        </ContentTile>

        <ContentTile>
          <h2>Urlaub im Weinviertel</h2>
          <p>Nehmen Sie sich ein paar Tage Auszeit und genießen Sie die blühende Landschaft rund um Schrattenthal.</p>
          <img class="img-fluid"
                     :src="require('../../images/202006_weingarten.jpg')"
                     alt="Weingarten Winzerhof Wurst">
        </ContentTile>

        <ContentTile>
            <h2>Urlaub am Winzerhof</h2>
            <div class="embed-responsive embed-responsive-16by9">
              <iframe width="640" height="360" src="https://www.youtube.com/embed/O2i49NVaYNs" frameborder="0" allowfullscreen></iframe>
            </div>
        </ContentTile>

        <NewsRetzbacherhof />
        <NewsSchlossSchrattenthal />
        <NewsRentARebstock />
    </Content>
</template>

<script>
import Content from "../../components/Content.vue";
import ContentTile from "../../components/ContentTile.vue";
import NewsMarketLeonding from "../../components/NewsMarketLeonding.vue";
import NewsRentARebstock from "../../components/NewsRentARebstock.vue";
import NewsRetzbacherhof from "../../components/NewsRetzbacherhof.vue";
import NewsSchlossSchrattenthal from "../../components/NewsSchlossSchrattenthal.vue";

export default {
  components: {
    Content,
    ContentTile,
    NewsMarketLeonding,
    NewsRentARebstock,
    NewsRetzbacherhof,
    NewsSchlossSchrattenthal
  }
};
</script>
