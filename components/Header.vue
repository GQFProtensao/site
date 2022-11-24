<template>
  <header
    class="fixed w-full z-30 md:bg-opacity-90 transition duration-300 ease-in-out"
    :class="{ ['bg-green-primary backdrop-blur-sm shadow-lg']: !top }"
  >
    <div class="max-w-6xl mx-auto px-5 sm:px-6">
      <div class="flex items-center justify-between h-16 md:h-20">
        <div class="flex-shrink-0 mr-4">
          <NuxtLink to="/" class="block" aria-label="Cruip">
            <img
              class="w-20 h-20"
              src="@/assets/logo.svg"
              alt="Logo GQF Protesões"
            />
          </NuxtLink>
        </div>

        <nav class="flex flex-grow">
          <ul class="flex flex-grow justify-end flex-wrap items-center">
            <li>
              <NuxtLink
                to="/signin"
                class="font-medium text-gray-600 hover:text-gray-900 px-5 py-3 flex items-center transition duration-150 ease-in-out"
                >Entrar
              </NuxtLink>
            </li>
            <li>
              <NuxtLink
                to="/signup"
                class="btn-sm text-gray-200 bg-gray-900 hover:bg-gray-800 ml-3"
              >
                <span>Registrar</span>
                <svg
                  class="w-3 h-3 fill-current text-gray-400 flex-shrink-0 ml-2 -mr-1"
                  viewBox="0 0 12 12"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M11.707 5.293L7 .586 5.586 2l3 3H0v2h8.586l-3 3L7 11.414l4.707-4.707a1 1 0 000-1.414z"
                    fill-rule="nonzero"
                  />
                </svg>
              </NuxtLink>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {
      top: true,
    }
  },
  mounted() {
    window.addEventListener('scroll', this.scrollHandler)
  },
  methods: {
    scrollHandler() {
      this.top = !(window.pageYOffset > 10)
    },
  },
})
</script>
