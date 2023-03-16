<template>
  <header class="container max-w-xl mx-auto sticky top-0 z-10">
    <div class="flex justify-end items-center p-4">
      <a href="https://github.com/ansidev/template-vite-vue-tailwind" class="text-gray-900 dark:text-gray-100 p-4"
        aria-label="GitHub Repository">
        <BsIcon icon="github" :size="20" />
      </a>
      <ThemeSwitcher />
    </div>
    <!-- START - Header Menu - Velocity.V6 -->

  <section class="sticky top-0 z-50 bg-gradient-to-r from-gray-700 to-gray-900">

    <nav class="px-8 lg:px-16 py-6">
      <div class="flex flex-wrap justify-between items-center mx-auto w-full">
        <a href="https://aidxn.com" class="flex items-center">
          <img src="image/aidxn-logo.svg" loading="eager" class="h-6 mr-3 sm:h-9" alt="Aiden Wood - Gold Coast Web Design and Digital Marketing" />
          <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white hidden">Aiden Wood - Gold Coast Web Design and Digital Marketing</span>
        </a>
        <button id="mega-menu-full-image-button" data-collapse-toggle="mega-menu-full-image" type="button" class="inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="mega-menu-full-image" aria-expanded="false">
          <span class="sr-only">Open main menu</span>
          <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path>
          </svg>
        </button>
        <div id="mega-menu-full-image" class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1">
          <ul class="flex flex-col mt-4 text-sm font-medium md:flex-row md:space-x-8 md:mt-0">
            <li>
              <a href="https://aidxn.com/" class="flex items-center justify-between w-full py-4 px-6 font-medium text-gray-300 md:w-auto hover:text-white hover:bg-gray-600 rounded-xl duration-100" aria-current="page">Home</a>
            </li>
            <li>
              <button id="mega-menu-full-cta-image-button" data-collapse-toggle="mega-menu-full-image-dropdown" class="flex items-center justify-between w-full py-4 px-6 font-medium text-gray-300 md:w-auto hover:text-white hover:bg-gray-600 rounded-xl duration-100">Services <svg class="w-4 h-4 ml-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd"></path>
                </svg></button>
            </li>
            <li>
              <a href="https://shop.sitelabanalytics.com/" class="flex items-center justify-between w-full py-4 px-6 font-medium text-gray-300 md:w-auto hover:text-white hover:bg-gray-600 rounded-xl duration-100">Shop</a>
            </li>
            <li>
              <a href="https://dev.aidxn.com/" class="flex items-center justify-between w-full py-4 px-6 font-medium text-gray-300 md:w-auto hover:text-white hover:bg-gray-600 rounded-xl duration-100">Login</a>
            </li>
            <li>
              <a href="https://pay.aidxn.com/" class="flex items-center justify-between w-full py-4 px-6 font-semibold text-gray-300 md:w-auto hover:text-white bg-purple-800 hover:bg-purple-600 rounded-xl duration-100">Get Started</a>
            </li>
          </ul>
        </div>
      </div>

      <!-- START - Mega Menu - Velocity.V6 -->
      <div id="mega-menu-full-image-dropdown" class="hidden mt-16 lg:mt-8 rounded border border-gray-300">
        <div class="grid w-full px-4 lg:px-8 py-16 lg:py-8 text-sm font-thin text-gray-500 dark:text-gray-400 md:grid-cols-3">
          <ul class="hidden mb-4 space-y-4 lg:space-y-8 md:mb-0 md:block" aria-labelledby="mega-menu-full-image-button">
            <li>
              <a href="https://shop.sitelabanalytics.com/" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                Online Store
              </a>
            </li>
            <li>
              <a href="https://aidxn.com/velocity/" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                Velocity Theme
              </a>
            </li>
            <li>
              <a href="https://aidxn.com/dns-optimisation" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                DNS Optimisation
              </a>
            </li>
            <li>
              <a href="https://aidxn.com/pageload-speed-optimiation" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                Pageload Speed Optimisation
              </a>
            </li>
          </ul>
          <ul class="mb-4 space-y-4 lg:space-y-8 md:mb-0">
            <li>
              <a href="https://blog.aidxn.com/" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                Design Blog
              </a>
            </li>
            <li>
              <a href="https://aidxn.com/website-design" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                Website Design
              </a>
            </li>
            <li>
              <a href="https://aidxn.com/brand-design" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                Brand Design
              </a>
            </li>
            <li>
              <a href="https://aidxn.com/ad-strategy-management" class="hover:underline hover:text-blue-600 dark:hover:text-blue-500">
                Ad Strategy & Management
              </a>
            </li>
          </ul>
          <a href="https://g2ok5807scs.typeform.com/to/tCmzlDza" class="p-8 text-left bg-local bg-gray-900 bg-center bg-no-repeat bg-cover rounded-lg bg-blend-multiply hover:bg-blend-soft-light dark:hover:bg-blend-darken" style="background-image: url(https://aidxn.com/image/Phone Funnel Background - grey SML.webp)">
            <p class="max-w-xl text-2xl font-thin mb-5 font-extrabold leading-tight tracking-tight text-white">Get started today, be online in 24 hours.</p>
            <button type="button" class="inline-flex items-center px-2.5 py-1.5 text-xs font-medium text-center text-white border border-white rounded-lg hover:bg-white hover:text-gray-900 focus:ring-4 focus:outline-none focus:ring-gray-700">
              Get started
              <svg class="w-4 h-4 ml-1 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z" clip-rule="evenodd"></path>
              </svg>
            </button>
          </a>
        </div>
      </div>
      <!-- END - Mega Menu - Velocity.V6 -->
      </div>
    </nav>

  </section>

  </header>
</template>
