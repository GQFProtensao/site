<template>
  <div v-show="visible">
    <div
      class="fixed inset-0 z-50 bg-white bg-opacity-75 transition-opacity backdrop-blur-sm"
    />
    <div
      :id="id"
      class="fixed inset-0 z-50 overflow-hidden flex items-center justify-center transform px-4 sm:px-6"
    >
      <div
        class="bg-white overflow-auto max-w-6xl w-full max-h-full"
        ref="{modalContent}"
      >
        <slot />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    id: {
      type: String,
      required: true,
    },
    visible: {
      type: Boolean,
      required: false,
    },
  },
})
</script>
