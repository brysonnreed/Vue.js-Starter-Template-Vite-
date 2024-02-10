<template>
  <main>
    <div>
      <h1>
        <span class="text-[#41b883]">Vue.js</span> Base Starter With
        <span class="text-yellow-300">Vite</span> &
        <span class="text-blue-500">TailwindCSS</span>
      </h1>
      <p>
        To get started with a base template, first navigate to src/App.vue and the delete the code
        inside the template. You can also delete the import statement inside the script tag on this
        page. Then, delete the component 'DefaultView.vue' which is located in the components folder
      </p>
      <a
        href="https://github.com/brysonnreed?tab=repositories"
        target="_blank"
        aria-label="Link to my other Github repositories"
        class="btn"
        >My Github Repos
      </a>
    </div>
  </main>
</template>

<script setup></script>

<style scoped>
main {
  background-color: #4a4a4a;
  width: 100%;
  color: #aaa;
  font-size: 20px;
}

main div {
  display: flex;
  max-width: 1200px;
  min-height: 100vh;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  gap: 20px;
  margin-left: auto;
  margin-right: auto;
}

h1 {
  font-size: 60px;
  font-weight: bold;
  color: white;
}

.btn {
  background-color: #41b883;
  transition: all 0.3s ease;
  color: white;
  text-decoration: none;
  padding: 15px 50px;
  font-size: 18px;
  line-height: 120%;
  width: 300px;
  margin-left: auto;
  margin-right: auto;
}
.btn:hover {
  background-color: #3e9f73;
}
</style>
