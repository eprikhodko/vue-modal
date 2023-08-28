<template>
  <div
    v-show="props.isModalOpen"
    class="modal-overlay fixed top-0 right-0 bottom-0 left-0 z-overlay bg-[#083C94] bg-opacity-60 flex items-center justify-center"
    @click="$emit('closeModal')"
  >
    <div
      class="modal-content max-w-384 tablet-medium:max-w-496 w-full bg-card-01 rounded-16 px-32 mobile-large:px-56 py-40 text-center mx-16"
    >
      <p class="flex flex-col items-center">
        some modal content some modal content some modal content some modal content some modal
        content some modal content some modal content
      </p>
    </div>
  </div>
</template>

<script setup lang="ts">
defineEmits(['closeModal'])

interface Props {
  isModalOpen: boolean
}

const props = defineProps<Props>()
</script>

<style scoped lang="scss">
.modal-overlay {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 999;
  background-color: rgba(8, 60, 148, 0.6);
  display: flex;
  justify-content: center;
  align-items: center;
}

.modal-content {
  max-width: 384px;
  width: 100%;
  background: #fff;
  border-radius: 16px;
  padding: 20px;
}
// modal-content max-w-384 tablet-medium:max-w-496 w-full bg-card-01 rounded-16 px-32 mobile-large:px-56 py-40 text-center mx-16

// modal-overlay fixed top-0 right-0 bottom-0 left-0 z-overlay bg-[#083C94] bg-opacity-60 flex items-center justify-center
</style>
