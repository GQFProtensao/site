<template>
  <section class="relative">
    <div
      class="absolute left-1/2 transform -translate-x-1/2 bottom-0 pointer-events-none"
      aria-hidden="true"
    >
      <svg
        width="1360"
        height="578"
        viewBox="0 0 1360 578"
        xmlns="http://www.w3.org/2000/svg"
      >
        <defs>
          <linearGradient
            id="illustration-01"
            x1="50%"
            y1="0%"
            x2="50%"
            y2="100%"
          >
            <stop stop-color="#FFF" offset="0%" />
            <stop stop-color="#EAEAEA" offset="77.402%" />
            <stop stop-color="#DFDFDF" offset="100%" />
          </linearGradient>
        </defs>
        <g fill="url(#illustration-01)" fill-rule="evenodd">
          <circle cx="1232" cy="128" r="128" />
          <circle cx="155" cy="443" r="64" />
        </g>
      </svg>
    </div>

    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="pt-32 pb-12 md:pt-40 md:pb-20">
        <div class="text-center pb-12 md:pb-16">
          <h1
            class="text-5xl md:text-6xl font-extrabold leading-tighter tracking-tighter mb-4"
            data-aos="zoom-y-out"
          >
            Faça sua construção
            <span
              class="bg-clip-text text-transparent bg-gradient-to-r from-blue-500 to-teal-400"
              >valer a pena</span
            >
          </h1>
          <div class="max-w-3xl mx-auto">
            <p
              class="text-xl text-gray-600 mb-8"
              data-aos="zoom-y-out"
              data-aos-delay="150"
            >
              Empresa especializada em construção civil com foco na tecnologia
              das lajes protendidas
            </p>
            <div
              class="max-w-xs mx-auto sm:max-w-none sm:flex sm:justify-center"
              data-aos="zoom-y-out"
              data-aos-delay="300"
            >
              <div>
                <a
                  class="btn text-white bg-blue-600 hover:bg-blue-700 w-full mb-4 sm:w-auto sm:mb-0"
                  href="#0"
                  >Entrar em contato</a
                >
              </div>
              <div>
                <a
                  class="btn text-white bg-gray-900 hover:bg-gray-800 w-full sm:w-auto sm:ml-4"
                  href="#0"
                  >Aprenda mais</a
                >
              </div>
            </div>
          </div>
        </div>

        <div>
          <div
            class="relative flex justify-center mb-8"
            data-aos="zoom-y-out"
            data-aos-delay="450"
          >
            <div class="flex flex-col justify-center">
              <img
                class="mx-auto"
                src="@/assets/hero-image.png"
                width="768"
                height="432"
                alt="Hero"
              />
              <svg
                class="absolute inset-0 max-w-full mx-auto md:max-w-none h-auto"
                width="768"
                height="432"
                viewBox="0 0 768 432"
                xmlns="http://www.w3.org/2000/svg"
                xmlnsXlink="http://www.w3.org/1999/xlink"
              >
                <defs>
                  <linearGradient
                    x1="50%"
                    y1="0%"
                    x2="50%"
                    y2="100%"
                    id="hero-ill-a"
                  >
                    <stop stop-color="#FFF" offset="0%" />
                    <stop stop-color="#EAEAEA" offset="77.402%" />
                    <stop stop-color="#DFDFDF" offset="100%" />
                  </linearGradient>
                  <linearGradient
                    x1="50%"
                    y1="0%"
                    x2="50%"
                    y2="99.24%"
                    id="hero-ill-b"
                  >
                    <stop stop-color="#FFF" offset="0%" />
                    <stop stop-color="#EAEAEA" offset="48.57%" />
                    <stop stop-color="#DFDFDF" stop-opacity="0" offset="100%" />
                  </linearGradient>
                  <radialGradient
                    cx="21.152%"
                    cy="86.063%"
                    fx="21.152%"
                    fy="86.063%"
                    r="79.941%"
                    id="hero-ill-e"
                  >
                    <stop stop-color="#4FD1C5" offset="0%" />
                    <stop stop-color="#81E6D9" offset="25.871%" />
                    <stop stop-color="#338CF5" offset="100%" />
                  </radialGradient>
                  <circle id="hero-ill-d" cx="384" cy="216" r="64" />
                </defs>
                <g fill="none" fill-rule="evenodd">
                  <circle
                    fill-opacity=".04"
                    fill="url(#hero-ill-a)"
                    cx="384"
                    cy="216"
                    r="128"
                  />
                  <circle
                    fill-opacity=".16"
                    fill="url(#hero-ill-b)"
                    cx="384"
                    cy="216"
                    r="96"
                  />
                  <g fill-rule="nonzero">
                    <use fill="#000" xlinkHref="#hero-ill-d" />
                    <use fill="url(#hero-ill-e)" xlinkHref="#hero-ill-d" />
                  </g>
                </g>
              </svg>
            </div>
            <button
              class="absolute top-full flex items-center transform -translate-y-1/2 bg-white rounded-full font-medium group p-4 shadow-lg"
              aria-controls="modal"
            >
              <svg
                class="w-6 h-6 fill-current text-gray-400 group-hover:text-blue-600 flex-shrink-0"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2 2 6.477 2 12s4.477 10 10 10zm0 2C5.373 24 0 18.627 0 12S5.373 0 12 0s12 5.373 12 12-5.373 12-12 12z"
                />
                <path d="M10 17l6-5-6-5z" />
              </svg>
              <span class="ml-3">Assistir tudo (2 min)</span>
            </button>
          </div>

          <Modal id="modal" ariaLabel="modal-headline" show="{videoModalOpen}">
            <div class="relative pb-9/16">
              <iframe
                class="absolute w-full h-full"
                src="https://www.youtube.com/embed/0zgF7IsLNfM"
                title="Video"
                allowFullScreen
              ></iframe>
            </div>
          </Modal>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  methods: {
    setVideoModalOpen() {},
  },
})
</script>
