<template>
  <div id="app" class="bg-gray-200 antialiased">
    <header class="flex justify-between bg-gray-900 px-4 py-3">
      <div>
        <svg class="h-8 w-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 400 300">
        <path d="M210.6 119.6c0 4.4-3.6 8-8 8s-8-3.6-8-8 3.4-8 8-8c4.6.1 8 3.7 8 8zm-32.8 16v2s-3.8-4.9-11.9-4.9c-13.3 0-23.8 10.2-23.8 24.2s10.3 24.2 23.8 24.2c8.2 0 11.9-5 11.9-5v2.1c0 1 .7 1.7 1.7 1.7h9.9v-46h-9.9c-1 0-1.7.9-1.7 1.7zm0 29.5c-1.8 2.7-5.5 5-9.9 5-7.8 0-13.8-4.9-13.8-13.2 0-8.3 6-13.2 13.8-13.2 4.3 0 8.2 2.4 9.9 5v16.4zm19-31.2h11.8v46h-11.8v-46zm175.5-1.2c-8.1 0-11.9 4.9-11.9 4.9v-25.8h-11.8V180h9.9c1 0 1.7-.9 1.7-1.7v-2.1s3.8 5 11.9 5c13.3 0 23.8-10.3 23.8-24.2.1-14-10.4-24.3-23.6-24.3zm-1.9 37.3c-4.5 0-8.1-2.3-9.9-5v-16.4c1.8-2.4 5.8-5 9.9-5 7.8 0 13.8 4.9 13.8 13.2 0 8.3-6 13.2-13.8 13.2zm-27.8-17.4V180h-11.8v-26c0-7.6-2.4-10.7-9.1-10.7-3.6 0-7.2 1.8-9.5 4.5v32.1h-11.8v-46h9.3c1 0 1.7.9 1.7 1.7v2c3.4-3.6 8-4.9 12.5-4.9 5.1 0 9.4 1.5 12.9 4.4 4.2 3.4 5.8 7.8 5.8 15.5zm-70.7-19.9c-8.1 0-11.9 4.9-11.9 4.9v-25.8h-11.8V180h9.9c1 0 1.7-.9 1.7-1.7v-2.1s3.8 5 11.9 5c13.3 0 23.8-10.3 23.8-24.2.2-14-10.2-24.3-23.6-24.3zM270 170c-4.5 0-8.1-2.3-9.9-5v-16.4c1.8-2.4 5.8-5 9.9-5 7.8 0 13.8 4.9 13.8 13.2 0 8.3-6 13.2-13.8 13.2zm-31.9-37.3c3.6 0 5.4.6 5.4.6v10.9s-9.8-3.3-15.9 3.7v32.2h-11.8v-46.2h9.9c1 0 1.7.9 1.7 1.7v2c2.3-2.6 7.1-4.9 10.7-4.9zm-122 43.1c-.6-1.5-1.2-3.1-1.8-4.4-1-2.2-2-4.3-2.8-6.2l-.1-.1c-8.4-18.4-17.5-37-27.1-55.3l-.4-.7c-1-1.8-2-3.8-2.9-5.8-1.2-2.2-2.4-4.5-4.4-6.7-3.9-4.9-9.5-7.6-15.5-7.6-6.1 0-11.6 2.7-15.7 7.3-1.8 2.2-3.2 4.5-4.4 6.7-1 2-2 3.9-2.9 5.8l-.4.7c-9.4 18.4-18.6 37-27.1 55.3l-.1.2c-.9 2-1.8 4-2.8 6.2-.6 1.3-1.2 2.8-1.8 4.4-1.6 4.5-2.1 8.8-1.5 13.2 1.3 9.2 7.5 16.9 15.9 20.3 3.2 1.3 6.5 2 9.9 2 1 0 2.2-.1 3.2-.2 4-.5 8.2-1.8 12.2-4.2 5-2.8 9.8-6.9 15.2-12.7 5.4 5.9 10.3 9.9 15.2 12.7 4 2.3 8.2 3.7 12.2 4.2 1 .1 2.2.2 3.2.2 3.4 0 6.9-.6 9.9-2 8.6-3.4 14.6-11.3 15.9-20.3 1-4.2.5-8.5-1.1-13zm-55.2 6.3c-6.6-8.3-10.9-16.2-12.4-22.8-.6-2.8-.7-5.3-.4-7.5.2-2 1-3.7 2-5.1 2.3-3.3 6.2-5.4 10.8-5.4s8.6 2 10.8 5.4c1 1.5 1.7 3.2 2 5.1.4 2.2.2 4.8-.4 7.5-1.5 6.6-5.8 14.4-12.4 22.8zm48.8 5.8c-.9 6.4-5.1 11.9-11.1 14.3-2.9 1.2-6.1 1.6-9.3 1.2-3.1-.4-6.1-1.3-9.3-3.2-4.4-2.4-8.8-6.2-14-11.9 8.1-9.9 13-19 14.8-27.1.9-3.8 1-7.2.6-10.4-.5-3.1-1.6-5.9-3.3-8.3-3.8-5.5-10.2-8.7-17.3-8.7s-13.5 3.3-17.3 8.7c-1.7 2.4-2.8 5.3-3.3 8.3-.5 3.2-.4 6.7.6 10.4 1.8 8.1 6.9 17.3 14.8 27.2-5 5.6-9.5 9.4-14 11.9-3.2 1.8-6.2 2.8-9.3 3.2-3.3.4-6.5-.1-9.3-1.2-6-2.4-10.3-8-11.1-14.3-.4-3.1-.1-6.1 1.1-9.5.4-1.2 1-2.4 1.6-3.9.9-2 1.8-4 2.8-6.1l.1-.2c8.4-18.2 17.5-36.9 26.9-55l.4-.7c1-1.8 2-3.8 2.9-5.6 1-2 2.1-3.8 3.4-5.4 2.6-2.9 6-4.5 9.8-4.5s7.2 1.6 9.8 4.5c1.3 1.6 2.4 3.4 3.4 5.4 1 1.8 2 3.8 2.9 5.6l.4.7c9.3 18.2 18.4 36.9 26.8 55.1v.1c1 2 1.8 4.2 2.8 6.1.6 1.5 1.2 2.7 1.6 3.9 1.2 3.1 1.6 6.2 1.1 9.4z" fill="#ff5a5f"/>
      </svg>
      </div>
      <div class="flex">
        <button>
        <svg class="h-8 w-8 fill-current text-gray-500" xmlns="http://www.w3.org/2000/svg"><path fill="none" d="M-1-1h582v402H-1z"/><g><path d="M4 10h24a2 2 0 000-4H4a2 2 0 000 4zm24 4H4a2 2 0 000 4h24a2 2 0 000-4zm0 8H4a2 2 0 000 4h24a2 2 0 000-4z"/></g></svg>
      </button>
      </div>
    </header>
    <section class="flex justify-between bg-gray-800 px-4 py-3">
      <div class="relative">
        <div class="absolute inset-y-0 left-0 flex items-center pl-3">
          <svg class="h-6 w-6 fill-current text-gray-500" xmlns="http://www.w3.org/2000/svg"><path fill="none" d="M-1-1h582v402H-1z"/><g><path d="M16.32 14.9l5.39 5.4a1 1 0 01-1.42 1.4l-5.38-5.38a8 8 0 111.41-1.41v-.01zM10 16a6 6 0 100-12 6 6 0 000 12z"/></g></svg>
        </div>
        <input class="bg-gray-900 focus:outline-none focus:bg-white focus:text-gray-900 text-white rounded-lg pl-10 pr-4 py-2" type="search" placeholder="Search by keywords">
      </div>
      <button class="inline-flex bg-gray-700 hover:bg-gray-600 focus:outline-none focus:shadow-outline rounded-lg shadow pl-3 pr-3">
        <span class="text-white font-medium">Filters</span>
      </button>
    </section>
    <main class="px-4 py-6">
      <h3 class="text-gray-900 text-xl">Los Angeles</h3>
      <p class="text-gray-600">
        Live like the stars in these luxurious Southern California Estates
      </p>
      <div class="mt-6">
        <div>
          <div>
            <img class="rounded-lg shadow-md h-64" src="https://images.unsplash.com/photo-1556955112-28cde3817b0a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2550&q=80" alt="house image">
          </div>
          <div class="relative px-4 -mt-16">
            <div class="bg-white rounded-lg px-4 py-4 shadow-lg">
              <div class="flex">
                <span class="inline-block px-2 py-1 leading-none bg-teal-200 text-teal-800 rounded-full font-semibold uppercase tracking-wide text-xs">Plus</span>
                <div class="ml-2 text-xs text-gray-600 font-semibold uppercase tracking-wide">
                  3 beds &bull; 2 baths
                </div>
            </div>
            <h4 class="mt-1 text-gray-900 font-semibold text-lg">Modern home in city center</h4>
            <div class="mt-1">
              <span class="text-gray-900">
                $1,400
              </span>
              <span class="ml-1 text-sm text-gray-600">/wk</span>
            </div>
            <div class="text-sm text-gray-600">
              34 reviews
            </div>
          </div>
          </div>
        </div>
      </div>
    </main>

  </div>
</template>

<script>
export default {
  name: 'app',
  components: {}
}
</script>

<style src="./assets/css/tailwind.css"></style>