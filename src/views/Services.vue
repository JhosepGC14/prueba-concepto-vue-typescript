<template>
  <section class="container">
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
    <CardService
      description="Av victor Alzamora 298, Urb. Barrio Médico Surquillo"
      title="Ingreso del vehículo al taller"
    />
  </section>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import CardService from "@/components/CardServices.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Services",
  components: {
    CardService,
  },
});
</script>

<style scoped lang="scss">
.container {
  max-width: 1360px;
  width: 100%;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  row-gap: 40px;

  @media (max-width: 1064px) {
    grid-template-columns: repeat(2, 1fr);
  }

  @media (max-width: 568px) {
    grid-template-columns: repeat(1, 1fr);
  }
}
</style>
