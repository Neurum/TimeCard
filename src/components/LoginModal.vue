<template>
  <div>
    <div class="flex justify-center pt-24">
      <img src="../assets/images/full-logo-header.png" alt="COA Logo" />
    </div>
    <div class="flex items-center justify-center w-screen h-screen md:mx-auto -mt-40">
      <!-- Modal content -->
      <div class="relative bg-white rounded-lg shadow-2xl dark:bg-gray-700">
        <div class="px-6 py-6 lg:px-8">
          <h3 class="mb-4 text-xl font-medium text-gray-900 dark:text-white">Sign in to COA Timecard System</h3>
          <form class="space-y-6" action="#">
            <div>
              <input
                type="text"
                name="text"
                id="text"
                class="bg-gray-50 border border-gray-300 text-gray-00 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                placeholder="username"
                required
              />
            </div>
            <div>
              <input
                type="password"
                name="password"
                id="password"
                placeholder="password"
                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                required
              />
            </div>
            <div class="flex justify-between">
              <div class="flex items-start">
                <div class="flex items-center h-5">
                  <input
                    id="remember"
                    type="checkbox"
                    value=""
                    class="w-4 h-4 border border-gray-300 rounded bg-gray-50 focus:ring-3 focus:ring-blue-300 dark:bg-gray-600 dark:border-gray-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800"
                    required
                  />
                </div>
                <label for="remember" class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300">Remember me</label>
              </div>
              <a href="#" class="text-sm text-blue-700 hover:underline dark:text-blue-500">Lost Password?</a>
            </div>
            <button
              type="submit"
              class="w-full text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
            >
              Login to your account
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style></style>
