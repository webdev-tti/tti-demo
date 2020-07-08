<template>
<div>
  <nav class="flex items-center justify-between flex-wrap bg-secondary-color px-6 py-4">
    <div class="flex items-center flex-shrink-0 text-white mr-6 lg:mr-12">
      <Logo class=" w-48 ml-auto mr-auto" />
      <span class="font-semibold text-xl tracking-tight"></span>
    </div>
    <div class="block lg:hidden">
      <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
      </button>
    </div>
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
      <div class="aaz-menu text-lg lg:flex-grow flex items-center">
        <a href="#responsive-header" class="text-primary-color hover:text-white px-4 h-24 flex items-center border-primary-color border-l-2 border-r-2 relative overflow-hidden">
          Products 
        </a>
        <a href="#responsive-header" class="text-primary-color hover:text-white px-4 h-24 flex items-center border-primary-color border-l-2 border-r-2 relative overflow-hidden">
          Applications 
        </a>
        <a href="#responsive-header" class="text-primary-color hover:text-white px-4 h-24 flex items-center border-primary-color border-l-2 border-r-2 relative overflow-hidden">
          Industries We Service  
        </a>
        <a href="#responsive-header" class="text-primary-color hover:text-white px-4 h-24 flex items-center border-primary-color border-l-2 border-r-2 relative overflow-hidden">
          Parts and Accessories 
        </a>
      </div>
      <div>
        <a href="#" class="inline-block text-lg px-4 py-2 leading-none border-2 rounded-full text-primary-color border-primary-color hover:border-white-color hover:text-white hover:bg-primary-color mt-4 lg:mt-0">1800 816 277</a>
      </div>
    </div>
  </nav>
  <div class="text-5xl-2 font-bold text-center text-white bg-primary-gradient pt-32 pb-16 py-12 -rotate-45">
    <h1>{{ title }}</h1>
  </div>
</div>
</template>

<script>
import Logo from '../assets/logo.svg?inline'

export default {
  name: 'Header',
  components: {
    Logo
  },
  props: {
    title: String
  }
}
</script>