<template>
    <Content>
        <h1>Termine</h1>

        <ContentTile>
          <h2>Weinviertel DAC Präsentation</h2>
          <p>
            Am 26. April 2022 k&ouml;nnen Sie am amadeus terminal 2 Salzburg und am 9. Mai 2022 im Designcenter Linz unsere Weinviertel DAC 2021 verkosten. Wir freuen uns &uuml;ber Ihren Besuch.  N&auml;here Informationen zur Veranstaltung finden Sie unter <a href="https://www.weinvierteldac.at" target="_blank">weinvierteldac.at</a>.
          <p>
            <i>
              26.4. in Salzburg<br>
              9.5. in Linz
            </i>
          </p>
        </ContentTile>

        <ContentTile>
          <h2>Weintour</h2>
          <p>
            Das Weinviertel &ouml;ffnet seine T&uuml;ren am 23. und 24. April 2022. Wir m&ouml;chten Sie in unseren gem&uuml;tlichen Innenhof einladen, unser gesamtes Sortiment zu verkosten.
          </p>
          <img class="img-fluid"
                     :src="require('../../images/2022_weintour.jpg')"
                     alt="Weintour Weinviertel">
          <p>
            <i>23.-24.4.</i>
          </p>
        </ContentTile>

        <ContentTile>
          <h2>Sommerkeller</h2>
          <p>
            Im Zuge unserer offenen Kellert&uuml;r bieten wir am 11. August 2022 einen gem&uuml;tlichen Abend mit musikalischer Umrahmung. Um Tischreservierung wird gebeten.
          </p>
          <p>
             <i>11.8.</i>
          </p>
        </ContentTile>

        <ContentTile>
          <h2>Tag der offenen Kellertür</h2>
          <p>
            <p>Von 11. bis 14. August 2022 m&ouml;chten wir Sie recht herzlich zu unserer offenen Kellert&uuml;r einladen. Neben regionalen, herzhaften Schmankerln k&ouml;nnen Sie auch Petras Mehlspeisen mit einem Achterl Wein bei unserem Presshaus genie&szlig;en. <br>Wir sind am Donnerstag und Freitag ab 17 Uhr und Samstag und Sonntag ab 15 Uhr f&uuml;r Sie da.
          </p>
          <p>
             <i>11.-14.8.</i>
          </p>
        </ContentTile>

        <NewsMarketLeonding />
    </Content>
</template>

<script>
import Content from "../../components/Content.vue";
import ContentTile from "../../components/ContentTile.vue";
import NewsMarketLeonding from "../../components/NewsMarketLeonding.vue";

export default {
  components: {
    Content,
    ContentTile,
    NewsMarketLeonding,
  }
};
</script>
