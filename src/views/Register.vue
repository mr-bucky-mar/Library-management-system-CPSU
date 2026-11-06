<template>
  <div class="min-h-screen bg-gradient-to-r from-green-900 to-green-500 flex items-center justify-center p-10">

    <div class="bg-white rounded-3xl overflow-hidden shadow-2xl flex w-[1100px]">

      <!-- Left Side -->

      <div class="w-2/5 bg-gradient-to-b from-green-800 to-green-600 text-white p-10 flex flex-col justify-center">

        <div class="flex justify-center">
          <img src="/library-logo.png" class="w-24 h-24" />
        </div>

        <h1 class="text-center text-5xl font-bold mt-6">
          CPSU
        </h1>

        <h2 class="text-center text-3xl">
          Library System
        </h2>

        <p class="text-center mt-8 text-lg">
          Your gateway to knowledge,
          resources, and learning at
          Central Philippines State University.
        </p>

        <p class="text-center mt-8">
          Learn • Read • Discover
        </p>

      </div>

      <!-- Right Side -->

      <div class="w-3/5 p-10">

        <h1 class="text-5xl font-bold text-green-800">
          Create Account
        </h1>

        <p class="text-gray-500 mt-2">
          Join the CPSU Library System
        </p>

        <div class="space-y-5 mt-8">

          <input
            type="text"
            placeholder="Student ID"
            class="w-full border p-4 rounded-xl"
          />

          <input
            type="text"
            placeholder="Full Name"
            class="w-full border p-4 rounded-xl"
          />

          <input
            type="email"
            placeholder="Email Address"
            class="w-full border p-4 rounded-xl"
          />

          <input
            type="password"
            placeholder="Password"
            class="w-full border p-4 rounded-xl"
          />

          <input
            type="password"
            placeholder="Confirm Password"
            class="w-full border p-4 rounded-xl"
          />

        </div>

        <button
          class="w-full mt-8 bg-green-500 text-white py-4 rounded-xl font-semibold"
        >
          Create Account →
        </button>

        <p class="text-center mt-6">
          Already have an account?
          <router-link
            to="/login"
            class="text-green-700 font-semibold"
          >
            Login here
          </router-link>
        </p>

        <div class="text-center mt-4">
          <router-link
            to="/"
            class="border rounded-xl px-5 py-3 inline-block text-green-700"
          >
            ← Back to Welcome
          </router-link>
        </div>

      </div>

    </div>

  </div>
</template>