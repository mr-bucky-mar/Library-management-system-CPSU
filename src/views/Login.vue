<script setup>
import { ref } from 'vue'
import SuccessModal from '../components/SuccessModal.vue'

const showModal = ref(false)

const login = () => {
  showModal.value = true

  setTimeout(() => {
    window.location.href = '/dashboard'
  }, 2000)
}
</script>

<template>
  <div class="min-h-screen bg-gradient-to-r from-green-900 to-green-500 flex items-center justify-center">

    <div class="bg-white rounded-3xl w-[550px] p-10 shadow-xl">

      <div class="flex justify-center">
        <img src="/library-logo.png" class="w-20 h-20" />
      </div>

      <h1 class="text-center text-4xl font-bold text-green-800 mt-4">
        CPSU
      </h1>

      <h2 class="text-center text-2xl">
        Library System
      </h2>

      <p class="text-center text-gray-500 mt-2">
        Welcome back! Please login to continue.
      </p>

      <div class="mt-8">
        <label class="font-semibold">Student ID</label>
        <input
          type="text"
          class="w-full border rounded-lg p-4 mt-2"
        />
      </div>

      <div class="mt-5">
        <label class="font-semibold">Password</label>
        <input
          type="password"
          class="w-full border rounded-lg p-4 mt-2"
        />
      </div>

      <button
        @click="login"
        class="w-full mt-8 bg-green-500 text-white py-4 rounded-xl font-semibold"
      >
        Login →
      </button>

      <p class="text-center mt-5 text-gray-500">
        Don't have an account?
        <router-link to="/register" class="text-green-700 font-semibold">
          Sign Up
        </router-link>
      </p>

      <div class="text-center mt-5">
        <router-link
          to="/"
          class="text-green-700 font-medium"
        >
          ← Back to Welcome
        </router-link>
      </div>

    </div>

    <SuccessModal
      v-if="showModal"
    />

  </div>
</template>