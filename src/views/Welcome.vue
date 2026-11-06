<template>
  <div class="min-h-screen bg-gradient-to-r from-green-900 to-green-500 flex items-center justify-center">

    <div class="bg-white w-[500px] rounded-3xl p-10 text-center shadow-xl">

      <div class="flex justify-center mb-4">
        <img src="/library-logo.png" class="w-20 h-20" />
      </div>

      <h1 class="text-4xl font-bold text-green-800">
        CPSU Library System
      </h1>

      <h2 class="text-2xl mt-2 font-semibold">
        Welcome!
      </h2>

      <p class="text-gray-500 mt-4">
        Access the Central Philippines State University
        digital library system.
      </p>

      <router-link to="/login">
        <button
          class="w-full mt-8 bg-green-800 text-white py-4 rounded-xl font-semibold hover:bg-green-900"
        >
          Login
        </button>
      </router-link>

      <router-link to="/register">
        <button
          class="w-full mt-4 bg-green-500 text-white py-4 rounded-xl font-semibold hover:bg-green-600"
        >
          Sign Up
        </button>
      </router-link>

      <p class="text-gray-400 mt-8">
        Central Philippines State University
      </p>

    </div>

  </div>
</template>