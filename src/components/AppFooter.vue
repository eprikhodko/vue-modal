<template>
  <footer class="footer">
    <AppLogo />

    <div class="links-container">
      <div class="links-col" v-for="(col, index) in footerLinks" :key="index">
        <p class="links-col__title">{{ col.title }}</p>
        <a
          class="links-col__link"
          v-for="(link, linkIndex) in col.links"
          :key="linkIndex"
          :href="link.url"
          >{{ link.text }}</a
        >
      </div>
    </div>

    <p class="footer__copyright-text">© {{ year }}, Morda-Morda. All rights reserved.</p>
  </footer>
</template>

<script setup lang="ts">
import { footerLinks } from '../constants/links'
import AppLogo from './AppLogo.vue'

const year = new Date().getFullYear()
</script>

<style scoped lang="scss">
@import '../assets/scss/main.scss';

.footer {
  display: flex;
  flex-direction: column;
  max-width: 1216px;
  width: 100%;
  margin: auto;
  padding: 128px 0;
}

.links-container {
  display: flex;
  justify-content: space-between;
  margin: 32px 0 112px;
}

.links-col {
  display: flex;
  flex-direction: column;
  gap: 28px;

  &__title {
    font-weight: 700;
    font-size: 22px;
  }

  &__link {
    // font-family: 'Inter';
    font-size: 16px;
    font-weight: 500;
  }
}

.footer__copyright-text {
  font-size: 16px;
  font-weight: 700;
  color: $text-second;
}
</style>
