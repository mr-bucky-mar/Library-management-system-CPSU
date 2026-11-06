<template>

<div class="min-h-screen bg-gray-100">

  <!-- Navbar -->

  <nav class="bg-white shadow px-10 py-5 flex justify-between items-center">

    <div class="flex items-center gap-4">

      <img
        src="/library-logo.png"
        class="w-14 h-14"
      />

      <div>
        <h1 class="font-bold text-2xl text-green-800">
          CPSU Library
        </h1>

        <p class="text-gray-500 text-sm">
          Central Philippines State University
        </p>
      </div>

    </div>

    <button
      class="border-2 border-green-700 px-6 py-2 rounded-xl text-green-700 hover:bg-green-700 hover:text-white"
    >
      Logout
    </button>

  </nav>

  <!-- Hero -->

  <section class="px-12 py-10">

    <div
      class="bg-gradient-to-r from-green-900 to-green-500 rounded-3xl p-12 text-white flex justify-between items-center"
    >

      <div>

        <span
          class="bg-white/20 px-4 py-2 rounded-full"
        >
          CPSU STUDENT LIBRARY
        </span>

        <h1 class="text-5xl font-bold mt-6">
          Welcome to the CPSU Library!
        </h1>

        <p class="text-xl mt-5 max-w-2xl">
          Discover books, explore knowledge,
          and access valuable learning resources
          for your academic journey.
        </p>

        <button
          class="mt-8 bg-white text-green-800 px-6 py-3 rounded-xl font-semibold"
        >
          Browse Library →
        </button>

      </div>

      <div class="text-9xl">
        📖
      </div>

    </div>

  </section>

  <!-- Quick Access -->

  <section class="px-12">

    <h2 class="text-center text-4xl font-bold text-green-800">
      Quick Access
    </h2>

    <div class="grid md:grid-cols-3 gap-8 mt-10">

      <div class="bg-white rounded-3xl p-8 shadow text-center">
        <div class="text-6xl">📚</div>
        <h3 class="text-2xl font-bold mt-4">
          Books
        </h3>
      </div>

      <div class="bg-white rounded-3xl p-8 shadow text-center">
        <div class="text-6xl">🔍</div>
        <h3 class="text-2xl font-bold mt-4">
          Search
        </h3>
      </div>

      <div class="bg-white rounded-3xl p-8 shadow text-center">
        <div class="text-6xl">📖</div>
        <h3 class="text-2xl font-bold mt-4">
          Borrowed Books
        </h3>
      </div>

    </div>

  </section>

</div>

</template>