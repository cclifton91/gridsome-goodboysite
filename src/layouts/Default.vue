<template>
  <div class="flex flex-col min-h-screen bg-black">
    <header class="fixed mx-auto bg-black w-full py-5 pr-12 top-0 sm:flex sm:justify-between z-10">
      <div class="flex items-center justify-between">
        <div class="navwrapper flex w-full justify-between">
          <div>
            <a href="#home">
              <g-image alt="Goodboy logo" src="../../static/goodboylogosvg.svg" class="h-8" />
            </a>
          </div>
          <div>
            <button
              @click="isOpen = !isOpen"
              type="button"
              class="text-yellow-500 focus:text-white hover:text-white border border-yellow-500 py-2 px-2 rounded sm:hidden"
            >
              <svg width="24" height="24" class="fill-current" v-if="!isOpen">
                <rect width="24" height="24" fill="none" rx="0" ry="0" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M4 7C4 6.58579 4.33579 6.25 4.75 6.25H19.25C19.6642 6.25 20 6.58579 20 7C20 7.41421 19.6642 7.75 19.25 7.75H4.75C4.33579 7.75 4 7.41421 4 7ZM4 12C4 11.5858 4.33579 11.25 4.75 11.25H19.25C19.6642 11.25 20 11.5858 20 12C20 12.4142 19.6642 12.75 19.25 12.75H4.75C4.33579 12.75 4 12.4142 4 12ZM4.75 16.25C4.33579 16.25 4 16.5858 4 17C4 17.4142 4.33579 17.75 4.75 17.75H19.25C19.6642 17.75 20 17.4142 20 17C20 16.5858 19.6642 16.25 19.25 16.25H4.75Z"
                />
              </svg>
              <svg width="24" height="24" class="fill-current" v-if="isOpen">
                <rect width="24" height="24" fill="none" rx="0" ry="0" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M13.4049 12.0025L18.6949 6.7125C19.0849 6.3225 19.0849 5.6925 18.6949 5.3025C18.3049 4.9125 17.6749 4.9125 17.2849 5.3025L11.9949 10.5925L6.70494 5.2925C6.31494 4.9025 5.68494 4.9025 5.29494 5.2925C4.90494 5.6825 4.90494 6.3125 5.29494 6.7025L10.5849 12.0025L5.29494 17.2925C4.90494 17.6825 4.90494 18.3125 5.29494 18.7025C5.48494 18.9025 5.73494 19.0025 5.99494 19.0025C6.25494 19.0025 6.50494 18.9025 6.70494 18.7125L11.9949 13.4125L17.2849 18.7025C17.4849 18.9025 17.7349 19.0025 17.9949 19.0025C18.2549 19.0025 18.5049 18.9025 18.7049 18.7125C19.0949 18.3225 19.0949 17.6925 18.7049 17.3025L13.4049 12.0025Z"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
      <nav
        :class="isOpen ? 'block' : 'hidden' "
        class="text-white py-6 pb-4 text-right sm:block sm:py-0"
      >
        <a
          href="#about"
          class="block text-yellow-500 sm:inline-block sm:mr-6 font-semibold hover:bg-gray-900 hover:text-white"
        >About</a>
        <a
          href="#services"
          class="block mt-2 text-yellow-500 sm:inline-block sm:mr-6 font-semibold hover:bg-gray-900 hover:text-white"
        >Services</a>
        <a
          href="#"
          class="block mt-2 text-yellow-500 sm:inline-block sm:mr-6 font-semibold hover:bg-gray-900 hover:text-white"
        >Testimonials</a>
        <a
          href="#"
          class="block mt-2 text-yellow-500 sm:inline-block sm:mr-6 font-semibold hover:bg-gray-900 hover:text-white"
        >Contact</a>
      </nav>
    </header>
    <main class="flex flex-col justify-center items-center">
      <slot />
    </main>
    <footer class="bg-yellow-500 text-black">
      <div class="container mx-auto flex flex-col sm:flex-row items-center justify-between py-8">
        <p class="font-body text-sm">Copyright 2020. All Rights Reserved.</p>
        <ul class="flex items-center mt-4 sm:mt-0">
          <li class="mr-8">
            <a href="/">
              <g-image alt="logo" src="../../static/icons8-facebook-30.png" width="30px" />
            </a>
          </li>
          <li class="mr-8">
            <a href="/">
              <g-image alt="logo" src="../../static/icons8-instagram-30.png" width="30px" />
            </a>
          </li>
          <li class="mr-8">
            <a href="/">
              <a href="/">
                <g-image alt="logo" src="../../static/icons8-twitter-squared-30.png" width="30px" />
              </a>
            </a>
          </li>
        </ul>
      </div>
    </footer>
  </div>
</template>


<script>
export default {
  data() {
    return {
      isOpen: true
    };
  }
};
</script>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>
