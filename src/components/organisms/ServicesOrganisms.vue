<template>
    <div class="services">
      <ServiceMolecules title="Front End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima beatae enim tenetur, dicta id tempore asperiores iste quasi aliquid, veniam consequuntur ratione nulla incidunt maxime sunt nostrum rem quis! Eos."
     />

      <ServiceMolecules
        title="Back End"
        description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima beatae enim tenetur, dicta id tempore asperiores iste quasi aliquid, veniam consequuntur ratione nulla incidunt maxime sunt nostrum rem quis! Eos."
      />
      <ServiceMolecules
        title="Manutenção"
        description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima beatae enim tenetur, dicta id tempore asperiores iste quasi aliquid, veniam consequuntur ratione nulla incidunt maxime sunt nostrum rem quis! Eos."
      />
    </div>
</template>

<script setup lang="ts">
import { ServiceMolecules } from '../molecules';

</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>