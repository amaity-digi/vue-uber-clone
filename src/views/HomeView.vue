<template>
  <div id="HOME" class="flex flex-col h-screen">
    <div class="m-3 mb-auto">

      <div class="grid grid-cols-2 gap-3 my-3">
        <ServiceSelectLarge text="Ride" imgageWidth="100" image="ride" />
        <ServiceSelectLarge text="Food" imgageWidth="100" image="food" promo="true" />
      </div>

      <div class="grid grid-cols-4 gap-3 my-3">
        <ServiceSelectSmall text="Travel" image="travel" />
        <ServiceSelectSmall text="2 Wheels" image="2wheels" />
        <ServiceSelectSmall text="Transit" image="transit" />
        <ServiceSelectSmall text="Reserve" image="reserve" />
      </div>
      <div>
        <mdiMagnify size="40" />
      </div>

    </div>
  </div>
</template>

<script setup>
import ServiceSelectSmall from '@/components/ServiceSelectSmall.vue';
import ServiceSelectLarge from '../components/ServiceSelectLarge.vue'
</script>
