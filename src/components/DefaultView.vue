<template>
  <section class="bg-gray-700 min-h-screen flex justify-center items-center px-5">
    <div class="grid lg:grid-cols-2 gap-20 lg:gap-5 container mx-auto">
      <div class="text-[#aaa] flex flex-col gap-10">
        <div>
          <h1>
            <span class="text-[#41b883]">Vue.JS </span>Starter Base Template Built with
            <span class="text-[#41b883] animate-pulse hidden lg:inline-block">-></span>
          </h1>
          <p class="text-lg">
            To get started with a base template, first navigate to src/App.vue and the delete the
            code inside the template. You can also delete the import statement inside the script tag
            on this page. Then, delete the component 'DefaultView.vue' which is located in the
            components folder
          </p>
        </div>
        <div>
          <a
            href="https://github.com/brysonnreed?tab=repositories"
            target="_blank"
            aria-label="Link to my other Github repositories"
            class="btn px-5 py-3"
            >My Github Repos
          </a>
        </div>
      </div>
      <div class="text-gray-600 body-font">
        <div class="container mx-auto flex flex-wrap">
          <div class="flex flex-col gap-5">
            <div>
              <div
                class="flex bg-[#e4e4e4] border-2 rounded-lg border-gray-200 border-opacity-50 p-5 sm:flex-row flex-col"
              >
                <div
                  class="w-16 h-16 sm:mr-8 sm:mb-0 mb-4 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0"
                >
                  <img src="https://vitejs.dev/logo-with-shadow.png" alt="Vite Logo" />
                </div>
                <div class="flex-grow">
                  <h2 class="text-gray-900 text-lg font-semibold mb-1">Vite</h2>
                  <p class="leading-relaxed text-base line-clamp-2">
                    Vite is a next-generation front-end dev tool, aiming to improve the developer
                    experience of webpack when it comes to developing JavaScript applications. Here,
                    Vite will divide your JavaScript modules into two categories while starting the
                    development build.
                  </p>
                  <a
                    href="https://vitejs.dev/"
                    class="mt-3 text-indigo-500 inline-flex items-center"
                    >Learn More
                    <svg
                      fill="none"
                      stroke="currentColor"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      class="w-4 h-4 ml-2"
                      viewBox="0 0 24 24"
                    >
                      <path d="M5 12h14M12 5l7 7-7 7"></path>
                    </svg>
                  </a>
                </div>
              </div>
            </div>
            <div>
              <div
                class="flex border-2 bg-[#e4e4e4] rounded-lg border-gray-200 border-opacity-50 p-5 sm:flex-row flex-col"
              >
                <div
                  class="w-16 h-16 sm:mr-8 sm:mb-0 mb-4 inline-flex items-center justify-center rounded-full bg-indigo-100 text-indigo-500 flex-shrink-0"
                >
                  <img
                    src="https://tailwindcss.com/_next/static/media/tailwindcss-mark.3c5441fc7a190fb1800d4a5c7f07ba4b1345a9c8.svg"
                    alt="TailwindCSS logo"
                  />
                </div>
                <div class="flex-grow">
                  <h2 class="text-gray-900 text-lg font-semibold mb-1">TailwindCSS</h2>
                  <p class="leading-relaxed text-base line-clamp-2">
                    Tailwind CSS is a utility-first CSS (Cascading Style Sheets) framework with
                    predefined classes that you can use to build and design web pages directly in
                    your markup. It lets you write CSS in your HTML in the form of predefined
                    classes.
                  </p>
                  <a
                    href="https://tailwindcss.com/"
                    class="mt-3 text-indigo-500 inline-flex items-center"
                    >Learn More
                    <svg
                      fill="none"
                      stroke="currentColor"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      class="w-4 h-4 ml-2"
                      viewBox="0 0 24 24"
                    >
                      <path d="M5 12h14M12 5l7 7-7 7"></path>
                    </svg>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
h1 {
  font-size: 60px;
  font-weight: bold;
  color: white;
  line-height: 100%;
  padding-bottom: 20px;
}

.btn {
  background-color: #41b883;
  transition: all 0.3s ease;
  color: white;
}
.btn:hover {
  background-color: #3e9f73;
}
</style>
