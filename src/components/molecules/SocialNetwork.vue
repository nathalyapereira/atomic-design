<template>
    <div class="social-networks">
        <SocialLink name="Github" to="https://github.com" icon="github.svg"/>
        <SocialLink name="Twitter" to="https://twitter.com" icon="twitter.svg"/>
        <SocialLink name="Facebook" to="https://facebook.com" icon="facebook.svg"/>

    </div>
</template>

<script setup lang="ts">
import { SocialLink } from '@/components/atoms';

</script>

<style lan="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>