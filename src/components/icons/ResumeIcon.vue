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
      d="m426-330 195-125q14-9 14-25t-14-25L426-630q-15-10-30.5-1.5T380-605v250q0 18 15.5 26.5T426-330Zm54 250q-83 0-156-31.5T197-197q-54-54-85.5-127T80-480q0-83 31.5-156T197-763q54-54 127-85.5T480-880q83 0 156 31.5T763-763q54 54 85.5 127T880-480q0 83-31.5 156T763-197q-54 54-127 85.5T480-80Z"
    />
  </svg>
</template>

<script setup lang="ts">
  import { getIconSize, type FillIconProps } from './utils'

  defineProps<FillIconProps>()
</script>
