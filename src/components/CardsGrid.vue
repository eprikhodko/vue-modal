<template>
  <div class="cards-grid">
    <slot />
  </div>
</template>

<style scoped lang="scss">
.cards-grid {
  display: grid;
  gap: 32px;
  grid-template-columns: repeat(12, 1fr);
}
</style>
