<template>
  <div class="cardContainer">
    <h4 class="cardContainer__title">{{ title }}</h4>
    <div class="cardContainer__boxBody">
      <p class="cardContainer__boxBody__description">{{ description }}</p>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "CardServices",
  props: {
    title: String,
    description: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.cardContainer {
  border: 3px solid #edeffc;
  box-sizing: border-box;
  border-radius: 16px;
  padding: 15px;
  max-width: 256px;
  margin: auto;

  &__title {
    font-family: Lato;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #141938;
  }

  &__boxBody {
    &__description {
      font-family: Roboto;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 24px;
      color: #141938;
    }
  }
}
</style>
