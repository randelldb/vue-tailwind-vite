<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="flex flex-wrap flex-col bg-gray-900 h-screen">

    <header class="w-full">

      <div class="flex flex-row justify-end bg-gray-800"><!-- top line -->
        <div>Log in</div>
        <div>Sign up</div>
      </div>

      <div class="flex flex-row justify-around bg-gray-700 h-20">

        <img src="grab-logo.png" alt="logo" class="object-cover h-3/4 self-center">

        <nav class=" bg-slate-300 self-center">
          <ul class="bg-yellow-200 flex flex-row">
            <li class="p-2">Home</li>
            <li class="p-2">About</li>
            <li class="p-2">About</li>
            <li class="p-2">Products</li>
            <li class="p-2">Career</li>
            <li class="p-2">Contact</li>
          </ul>
        </nav>
      </div>

    </header>

    <div class="flex flex-row flex-auto">

      <div class="flex flex-col bg-teal-700 w-40 items-center gap-2 p-2"> <!-- sidebar -->
        <div class="h-32 w-32 rounded-lg bg-gray-900">a</div>
        <div class="h-32 w-32 rounded-lg bg-gray-900">b</div>
        <div class="h-32 w-32 rounded-lg bg-gray-900">c</div>
        <div class="h-32 w-32 rounded-lg bg-gray-900">d</div>
      </div>
      
      <main class="flex flex-row flex-wrap flex-auto gap-5 justify-center m-10 "> <!-- maincontent -->

        <div class="bg-gradient-to-br from-gray-900 to-teal-700 rounded-lg w-1/3 h-80 drop-shadow-xl p-0.5">
          <div class="bg-gray-800 rounded-lg w-full h-full">1a</div>
        </div>

        <div class="bg-gradient-to-br from-gray-900 to-teal-700 rounded-lg w-1/3 h-80 drop-shadow-xl p-0.5">
          <div class="bg-gray-800 rounded-lg w-full h-full">1a</div>
        </div>

        <div class="bg-gradient-to-br from-gray-900 to-teal-700 rounded-lg w-1/3 h-80 drop-shadow-xl p-0.5">
          <div class="bg-gray-800 rounded-lg w-full h-full">1a</div>
        </div>

        <div class="bg-gradient-to-br from-gray-900 to-teal-700 rounded-lg w-1/3 h-80 drop-shadow-xl p-0.5">
          <div class="bg-gray-800 rounded-lg w-full h-full">1a</div>
        </div>
      </main>

    </div>

  </div>

</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
