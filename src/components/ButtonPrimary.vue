<template>
  <button type="button" class="button button--primary">{{ props.text }}</button>
</template>

<script setup lang="ts">
interface Props {
  text: string
}

const props = defineProps<Props>()
</script>

<style scoped lang="scss">
.button {
  border: none;
  border-radius: 8px;
  padding: 8px 24px;
  cursor: pointer;
}

.button--primary {
  background-color: #ff6490;
  color: #fff;
  font-size: 20px;
  font-weight: 600;
  transition: background-color 300ms;

  &:hover {
    background-color: #c74e70;
  }
}
</style>
