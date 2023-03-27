<template>
    <div class="presentation">
        <SocialNetwork />

        <img src="@/assets/images/presentation.svg" alt="Apresentação">
    </div>
</template>

<script setup lang="ts">
import { SocialNetwork } from '../molecules';
</script>

<style lang="scss" scoped>
.presentation {
  position: relative;
  display: grid;
  justify-content: center;
  .presentation {
    width: 80%;
    justify-self: center;
  }
  .social-networks {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
  }
}
</style>