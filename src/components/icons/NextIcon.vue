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
      d="M660-280v-400q0-17 11.5-28.5T700-720q17 0 28.5 11.5T740-680v400q0 17-11.5 28.5T700-240q-17 0-28.5-11.5T660-280Zm-440-35v-330q0-18 12-29t28-11q5 0 11 1t11 5l248 166q9 6 13.5 14.5T548-480q0 10-4.5 18.5T530-447L282-281q-5 4-11 5t-11 1q-16 0-28-11t-12-29Z"
    />
  </svg>
</template>

<script setup lang="ts">
  import { getIconSize, type FillIconProps } from './utils'

  defineProps<FillIconProps>()
</script>
