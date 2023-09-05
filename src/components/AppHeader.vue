<template>
  <header class="header">
    <AppLogo />
    <ButtonPrimary text="Open Modal" />
  </header>
</template>

<script setup lang="ts">
import ButtonPrimary from './ButtonPrimary.vue'
import AppLogo from './AppLogo.vue'
</script>

<style scoped lang="scss">
.header {
  width: 100%;
  max-width: 1440px;
  padding: 0 112px;
  position: fixed;
  background: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 999;
}
</style>
