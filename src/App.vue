<script setup lang="ts">
import Content from "./components/Content.vue";
</script>

<template>
  <header>Project name</header>
  <main>
    Project content
    <Content />
  </main>
  <footer>
    <hr />
    <a href="http://github.com/peruibeloko/template-vue">Link to source</a>
  </footer>
</template>

<style>
html,
body,
#app {
  height: 100%;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
}

#app {
  justify-content: center;
  align-items: center;
}

header,
main,
footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

main {
  flex-grow: 1;
}

header,
footer {
  height: 5rem;
  width: 100%;
}

footer hr {
  width: 80%;
}

footer a {
  margin-top: 1rem;
}

* {
  background-color: transparent;
  margin: 0;
  padding: 0;
  text-decoration: none;
}

html,
body {
  background-color: var(--background);
  color: var(--foreground);
}
</style>
