<template>
    <header class="header">
        <PortfolioLogo />
        <NavBar />
        <SearchForm />
    </header>
</template>

<script setup lang="ts">
import { PortfolioLogo } from '../atoms';
import { NavBar, SearchForm } from '../molecules';
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-between;
}
</style>