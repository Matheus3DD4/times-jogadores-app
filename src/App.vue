<template>
  <header>
    <span class="texto-header">Home</span>
    <span class="separador"> | </span>
    <span class="texto-header"> Jogadores </span>
    <span class="separador"> | </span>
    <span class="texto-header"> Times </span>
  </header>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}

header,
footer {
  background-color: rgb(14, 60, 1);
  height: 15%;
  font-size: 1.3em;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
}

main {
  min-height: 70%;
}

header span {
  padding: 0 10px;
}
</style>
