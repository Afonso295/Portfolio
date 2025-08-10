<template>
  <div class="container-nl1">
    <div class="nome">AC</div>

    <div class="container-nl2">
      <a href="#home">Home</a>
      <a href="#sobre">Sobre</a>
      <a href="#educacao">Educação</a>
      <a href="#experiencia">Experiência</a>
      <a href="#projetos">Projetos</a>
      <a href="#contactos">Contactos</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
* {
  background-color: rgb(255, 255, 255);
}

.nome {
  color: rgb(45, 40, 192);
  font-size: 2vw;
  font-weight: bold;
}

.container-nl1 {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 5vw;
  height: 10vh;
  box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.1);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
}

.container-nl2 {
  display: flex;
  gap: 3vw;
  font-size: 1.2vw;
}

.container-nl2 a {
  text-decoration: none;
  color: inherit;
  cursor: pointer;
}

.container-nl2 a:hover {
  color: #007bff;
}
</style>
