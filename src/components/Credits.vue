<template>
  <footer>
    <hr />
    <ul>
      <li><a href="https://github.com/peruibeloko/template-vue">Source</a></li>
      <li>|</li>
      <li><a href="https://github.com/peruibeloko/">Other stuff</a></li>
      <li>|</li>
      <li><a href="https://carlinhos.dev.br">Me</a></li>
    </ul>
  </footer>
</template>

<style scoped>
footer {
  width: 100%;

  ul {
    display: flex;
    align-items: center;
    justify-content: center;

    list-style: none;
    display: flex;
    gap: 1rem;
    margin: 2rem 0;
  }

  hr {
    margin: auto;
    width: 80%;
    color: var(--bg2);
  }

  a {
    margin-top: 1rem;
    color: var(--aqua_dim);

    &:hover {
      color: var(--aqua);
    }
  }
}
</style>
