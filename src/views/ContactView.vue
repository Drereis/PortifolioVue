<template>
  <section class="Home3">
    <div class="home-content3">
      <h1>Entre em contato comigo</h1>
    </div>
    <form class="max-w-sm mx-auto">
      <div class="mb-5">
        <label
          for="email"
          class="block mb-2 text-sm font-medium text-purple-700 dark:text-white"
          >Your email</label
        >
        <input
          type="email"
          id="email"
          class="bg-gray-50 border border-gray-300 text-purple-700 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
          placeholder="name@flowbite.com"
          required
        />
      </div>
      <div class="mb-5">
        <label
          for="password"
          class="block mb-2 text-sm font-medium text-purple-700 dark:text-white"
          >Your password</label
        >
        <input
          type="password"
          id="password"
          class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
          required
        />
      </div>
      <div class="flex items-start mb-5">
        <div class="flex items-center h-5">
          <input
            id="remember"
            type="checkbox"
            value=""
            class="w-4 h-4 border border-purple-700 rounded-sm bg-gray-50 focus:ring-3 focus:ring-blue-300 dark:bg-purple-700 dark:border-purple-700 dark:focus:ring-purple-700 ddark:ring-offset-purple-700dark:focus:ring-offset-gray-800"
            required
          />
        </div>
        <label
          for="remember"
          class="ms-2 text-sm font-medium text-purple-900 dark:text-purple-700"
          >Remember me</label
        >
      </div>
      <button
        type="submit"
        class="text-white bg-black hover:bg-purple-800 focus:ring-4 focus:outline-none focus:ring-purple-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
      >
        Submit
      </button>
    </form>
  </section>
</template>
<script setup></script>
<style>
.home-content3 h1 {
  font-size: 56px;
  font-weight: 700px;
  margin: -3px 0;
  color: #ffffff;
  text-align: center;
}
#forms {
  width: 100%;
  max-width: 500px;
  margin: 0 auto;
  padding: 20px;
}
</style>
