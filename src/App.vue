<script setup lang="ts">
import Content from './components/Content.vue';
import Credits from './components/Credits.vue';
</script>

<template>
  <header>
    <h1>Project name</h1>
  </header>
  <main>
    <Content />
  </main>
  <Credits />
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

html,
body,
#app {
  height: 100%;
  display: flex;
  flex-direction: column;
  box-sizing: border-box;
}

html,
body {
  background-color: var(--bg_h);
  color: var(--fg);
}

#app {
  justify-content: center;
  align-items: center;
}

header {
  margin-top: 1rem;
  width: 100%;
}

main {
  flex-grow: 1;
}

header,
main {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
