<template>
    <ContainerBosons class="home-template">
    <HeaderOrganisms />
    <PresentationOrganisms />
    <ServicesOrganisms />
    </ContainerBosons >
    
</template>

<script setup lang="ts">
import { ContainerBosons } from '@/components/bosons'
import { HeaderOrganisms, PresentationOrganisms, ServicesOrganisms } from '@/components/organisms'

</script>

<style lang="scss" scoped>
.home-template {
  display: grid;
  grid-gap: 5rem;
  margin: 5rem auto;
}
</style>