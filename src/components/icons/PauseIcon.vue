<template>
  <svg
    :width="getIconSize($props)"
    :height="getIconSize($props)"
    viewBox="0 -960 960 960"
    class="min-w-[16px]"
    :class="fillColor ?? 'fill-current'"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M400-320q17 0 28.5-11.5T440-360v-240q0-17-11.5-28.5T400-640q-17 0-28.5 11.5T360-600v240q0 17 11.5 28.5T400-320Zm160 0q17 0 28.5-11.5T600-360v-240q0-17-11.5-28.5T560-640q-17 0-28.5 11.5T520-600v240q0 17 11.5 28.5T560-320ZM480-80q-83 0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Z"
    />
  </svg>
</template>

<script setup lang="ts">
  import { getIconSize, type FillIconProps } from './utils'

  defineProps<FillIconProps>()
</script>
