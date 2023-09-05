<template>
  <a href="#" class="grid-card" :class="classes">
    <div class="grid-card__image" :style="backgroundStyle"></div>
    <span class="grid-card__label">{{ props.label }}</span>
  </a>
</template>

<script setup lang="ts">
import { GridCardSizes } from '../constants/enums'

interface Props {
  size: GridCardSizes
  imgUrl: string
  label: string
}

const props = defineProps<Props>()

const classes = [
  { cardSizeM: props.size === GridCardSizes.MD },
  { cardSizeL: props.size === GridCardSizes.LG },
  { cardSizeXS: props.size === GridCardSizes.XS }
]

const backgroundStyle = {
  backgroundImage: `url(${props.imgUrl})`
}
</script>

<style scoped lang="scss">
@import '../assets/scss/main.scss';
.grid-card {
  overflow: hidden;
  border-radius: 16px;
  position: relative;

  &:hover &__image {
    transform: scale(1.08);
  }

  &__image {
  width: 100%;
  height: 100%;
  padding: 32px;
  background-size: cover;
  background-repeat: no-repeat;
  transition: transform 0.5s;
  will-change: transform; 

}

  &__label {
    font-size: 20px;
    font-weight: 600;
    color: $snow;
    background: $accent;
    border-radius: 999px;
    padding: 4px 16px;
    position: absolute;
    left: 32px;
    bottom: 32px;
  }
}


.cardSizeM {
  aspect-ratio: 592 / 400;
  grid-column: span 6;
}

.cardSizeL {
  aspect-ratio: 696 / 400;
  grid-column: span 7;
}

.cardSizeXS {
  aspect-ratio: 488 / 400;
  grid-column: span 5;
}
</style>
