<!-- <template>
  <div class="nuxt-welcome">
    <h1>Welcome to Your Nuxt.js App!</h1>
    <p>
      This is a simple welcome component created to get you started with your Nuxt.js project.
    </p>
    <nuxt-link to="/about" class="welcome-link">Learn more about us</nuxt-link>
  </div>
</template>

<script>
export default {
  name: 'NuxtWelcome',
};
</script>

<style scoped>
.nuxt-welcome {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  text-align: center;
  background-color: #f5f5f5;
  padding: 20px;
}

.nuxt-welcome h1 {
  font-size: 2.5em;
  margin-bottom: 0.5em;
}

.nuxt-welcome p {
  font-size: 1.2em;
  margin-bottom: 1em;
}

.welcome-link {
  display: inline-block;
  padding: 10px 20px;
  font-size: 1em;
  color: #fff;
  background-color: #007bff;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.welcome-link:hover {
  background-color: #0056b3;
}
</style> -->

<template>
  <div class="h-screen bg-gray-100 flex justify-center items-center">
    <div class="max-w-3xl mx-auto p-6 bg-white rounded-lg shadow-md">
      <div class="flex justify-center mb-6">
        <!-- <img src="~/assets/logo.png" alt="Logo" class="h-12 w-12"> -->
      </div>
      <h1 class="text-4xl font-bold text-gray-900 mb-4">Welcome to Your next Nuxt Project!</h1>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
        <div class="bg-blue-100 p-4 rounded-lg shadow-sm">
          <h2 class="text-2xl font-bold text-blue-500 mb-2">Get Started</h2>
          <p class="text-lg text-blue-600">Start building your application ultra fast with my starter.</p>
        </div>
        <div class="bg-green-100 p-4 rounded-lg shadow-sm">
          <h2 class="text-2xl font-bold text-green-500 mb-2">Explore Features</h2>
          <p class="text-lg text-green-600">This starter has TailwindCSS, Nuxt and ESLint pre-installed</p>
        </div>
      </div>
      <div class="flex justify-center mt-6">
        <nuxt-link to="https://marcopianaroli.com" class="bg-orange-500 hover:bg-orange-700 text-white font-bold py-2 px-4 rounded">Learn more about me</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NuxtWelcome',
};
</script>
