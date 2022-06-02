<template>
  <header>
    <div class="menu-esquerdo">
      <span> <RouterLink to="/"> Home </RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/"> Jogadores </RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/"> Times </RouterLink> </span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
  <RouterView />
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
  background-color: rgb(59, 59, 127);
  color: white;
  height: 15%;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 2rem;
  justify-content: space-between;
}

main {
  height: 70%;
}
header span {
  padding: 0 10px;
}
a {
  color: inherit;
  text-decoration: none;
}
</style>
