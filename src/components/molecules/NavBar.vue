<template>
    <nav class="nav-bar">
      <NavItem text="Serviços" to="/services" />
      <NavItem text="Sobre mim" to="/about" />
      <NavItem text="Cases" to="/cases" />
      <NavItem text="Contato" to="/contact" />
    </nav>
  </template>
  
  <script lang="ts" setup>

  import { NavItem } from '@/components/atoms'
  
 
  </script>
  
  <style lang="scss" scoped>
  .nav-bar {
    display: grid;
    grid-auto-flow: column;
    grid-gap: 2rem;
    width: max-content;
  }
  </style>