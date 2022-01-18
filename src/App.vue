<template>
  <div id="app">
    <div class="container">
      <h1>Todo List Manager</h1>
      <h6>Powered by Vue 3 | Vuex 4 | Axios | Ruby on Rails 6 | Postgres 13</h6>
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from "@/components/Todos.vue";

export default {
  name: "App",
  components: {
    Todos,
  },
};
</script>

<style>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}

.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
