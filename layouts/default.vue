<template>
  <div class="flex flex-col min-h-screen overflow-hidden font-inter">
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import aosMixin from '~/mixins/aos'

export default Vue.extend({
  mixins: [aosMixin],
})
</script>
