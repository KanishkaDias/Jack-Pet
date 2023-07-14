<!-- <script setup>
import { onMounted, ref } from "vue";

const navbar = ref('')
const showMenu = ref(false)

onMounted(() => {
   
})
</script> -->

<!-- <template>
  
  <nav class="bg-white border-gray-200 dark:bg-gray-900 fixed w-full z-20 ">
    <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
      <a href="#" class="flex items-center">
        <img src="./Image/My project.png" class="h-12 mr-3" alt="Flowbite Logo" />
        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">JACK PET</span>
      </a>

      <div class="flex md:order-2">
          <RouterLink @click="showMenu = false" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800" to="/signup">Sign up</RouterLink>
          <button data-collapse-toggle="navbar-cta" type="button" class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-cta" aria-expanded="false">
            <span class="sr-only">Open main menu</span>
            <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
          </button>
      </div>

      <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1" id="navbar-cta">
        <ul class="flex flex-col font-medium p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
          <li>
            <a href="#Home" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700" aria-current="page">Home</a>
          </li>
          <li>
            <a href="#AboutUs" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>
          </li>
          <li>
            <a href="#rescue" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Rescue</a>
          </li>
          <li>
            <RouterLink @click="showMenu = false" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700" to="/buy">Buy Now</RouterLink>
          </li> 
        
        </ul>
      </div>
    </div>
  </nav><br><br>

</template> -->

<!-- <template>
  <template>
    <nav ref="navbar" class="  petNavBar fixed top-0 left-0 w-full bg-primary-200 z-20 transition duration-200">
        
        <div class=" flex items-center justify-between h-20">
            <div class="relative z-30 flex items-center gap-2 mb-2 lg:mb-0">
                <h1 class=" mx-10 text-blue-950 font-bold text-lg lg:text-2xl">Jack<span class="text-sky-400 lg:text-4xl">Pets</span></h1>

                <img src="../../assets/images/pets.png" class="w-9 md:w-12" alt="head2">
            </div>
            <div class="flex lg:hidden items-center gap-2">
                <button
                    class=" text-white relative z-30 px-4 py-2 -mt-1.5 text-sm rounded-full  font-medium tracking-wider uppercase bg-sky-400 w-full lg:w-auto">subscribe</button>
                <button @click="showMenu = !showMenu" class="relative z-30 text-cyan-950 -mt-2 p-2">
                    <svg width="18" height="12" viewBox="0 0 18 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path
                            d="M1 12H17C17.55 12 18 11.55 18 11C18 10.45 17.55 10 17 10H1C0.45 10 0 10.45 0 11C0 11.55 0.45 12 1 12ZM1 7H17C17.55 7 18 6.55 18 6C18 5.45 17.55 5 17 5H1C0.45 5 0 5.45 0 6C0 6.55 0.45 7 1 7ZM0 1C0 1.55 0.45 2 1 2H17C17.55 2 18 1.55 18 1C18 0.45 17.55 0 17 0H1C0.45 0 0 0.45 0 1Z"
                            fill="black" />
                    </svg>
                </button>
            </div>
            <div class="
                  absolute lg:static top-20 inset-x-0 mx-10
                  flex flex-col lg:flex-row items-center gap-5 lg:gap-10
                  bg-primary-200 lg:bg-transparent pt-5 pb-10 px-5 lg:p-0
                  transition duration-500 lg:duration-200 lg:-translate-y-0
                " :class="!showMenu ? 'translate-y-[-150%]' : '-translate-y-0'">
                <RouterLink @click="showMenu = false" class="text-cyan-800 font-medium" to="/">Home</RouterLink>
                <RouterLink @click="showMenu = false" class="text-cyan-800 font-medium" to="/logIn">LogIn</RouterLink>
                
            </div>
        </div>
    </nav>
</template>
</template> -->

<script setup>
import { onMounted, ref } from "vue";

const navbar = ref('')
const showMenu = ref(false)

onMounted(() => {

})
</script>

<template>
  <nav ref="navbar" class="bg-white border-gray-200 dark:bg-gray-900 fixed w-full z-20">

    <div class=" flex items-center justify-between h-20">
      <a href="#" class="max-w-screen-xl flex flex-wrap items-center justify-between p-4">
        <img src="./Image/My project.png" class="h-12 mr-3 lg:pl-5" alt="Flowbite Logo" />
        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">JACK PET</span>
      </a>
      <div class="flex lg:hidden items-center gap-2">
        <button @click="showMenu = !showMenu" class="relative z-30 text-cyan-950 -mt-2 p-2">
          <svg width="18" height="12" viewBox="0 0 18 12" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M1 12H17C17.55 12 18 11.55 18 11C18 10.45 17.55 10 17 10H1C0.45 10 0 10.45 0 11C0 11.55 0.45 12 1 12ZM1 7H17C17.55 7 18 6.55 18 6C18 5.45 17.55 5 17 5H1C0.45 5 0 5.45 0 6C0 6.55 0.45 7 1 7ZM0 1C0 1.55 0.45 2 1 2H17C17.55 2 18 1.55 18 1C18 0.45 17.55 0 17 0H1C0.45 0 0 0.45 0 1Z"
              fill="black" />
          </svg>
        </button>
      </div>
      <div class="
                    absolute lg:static top-20 inset-x-0 mx-10
                    flex flex-col lg:flex-row items-center gap-5 lg:gap-10
                    bg-white lg:bg-transparent pt-5 pb-10 px-5 lg:p-64
                    transition duration-500 lg:duration-200 lg:-translate-y-0
                  " :class="!showMenu ? 'translate-y-[-150%]' : '-translate-y-0'">

        <a href="#Home"
          class=" font-medium block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
          aria-current="page">Home</a>
        <a href="#AboutUs"
          class="font-medium block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>
        <a href="#rescue"
          class="font-medium block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Rescue</a>
        <RouterLink @click="showMenu = false"
          class="font-medium block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
          to="/buy">Buy Now</RouterLink>



      </div>
      <div class="lg:p-8">
        <RouterLink @click="showMenu = false" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800 " to="/signup">Sign up</RouterLink>

      </div>

    </div>
  </nav>
</template>

<style></style>