<template>
  <div class="cta-block">
    <h1 class="cta-block__cta-title">Ready to Build a Modal Component?</h1>
    <p class="cta-block__cta-text">
      Unlock the power of Vue 3 by crafting your own custom modal. This essential UI element can
      elevate the user experience on any website or application.
    </p>

    <ButtonPrimary text="Open Modal" />
  </div>
</template>

<script setup lang="ts">
import ButtonPrimary from './ButtonPrimary.vue'
</script>

<style scoped lang="scss">
.cta-block {
  padding: 112px 56px;
  background-color: #fff0e2;
  border-radius: 24px;
  background-image: url('../assets/img/tuborg-cat.png');
  background-repeat: no-repeat;
  background-position: bottom right;

  &__cta-title {
    font-size: 48px;
    font-weight: 700;
    line-height: 56px;
    max-width: 500px;
    margin-bottom: 24px;
  }

  &__cta-text {
    font-size: 20px;
    font-weight: 600;
    max-width: 540px;
    margin-bottom: 40px;
  }
}
</style>
