<template>
    <Content>
        <h1>Termine</h1>

        <ContentTile>
          <h2>Weinviertel DAC Präsentation</h2>
          <p>
            26.4. Salzburg<br>
            9.5. Linz
          </p>
        </ContentTile>

        <ContentTile>
          <h2>Weintour</h2>
          <p>
            23.-24.4.
          </p>
        </ContentTile>

        <ContentTile>
          <h2>Sommerkeller</h2>
          <p>
             11.8.
          </p>
        </ContentTile>

        <ContentTile>
          <h2>Tag der offenen Kellertür</h2>
          <p>
             11.-14.8.
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
