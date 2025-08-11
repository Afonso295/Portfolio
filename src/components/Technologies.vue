<template>
  <div class="titulo">Technologies I Work With</div>
  <div class="technologies">
    <div class="technology-tag">
      <img
        src="/src/assets/Vue.js_Logo.svg"
        alt="Vue.js logo"
        class="tech-logo"
      />
      <span>Vue.js</span>
    </div>
    <div class="technology-tag">
      <img
        src="/src/assets/vitejs-logo.svg"
        alt="Vue.js logo"
        class="tech-logo"
      />
      <span>Vite</span>
    </div>
    <div class="technology-tag">
      <img
        src="/src/assets/HTML5_logo.svg"
        alt="Vue.js logo"
        class="tech-logo"
      />
      <span>HTML</span>
    </div>
    <div class="technology-tag">
      <img
        src="/src/assets/CSS3_logo.svg"
        alt="Vue.js logo"
        class="tech-logo"
      />
      <span>CSS</span>
    </div>
    <div class="technology-tag">
      <img
        src="/src/assets/JavaScript_logo.svg"
        alt="Vue.js logo"
        class="tech-logo"
      />
      <span>JavaScript</span>
    </div>
    <div class="technology-tag">
      <img
        src="/src/assets/github_logo.svg"
        alt="Vue.js logo"
        class="tech-logo"
      />
      <span>GitHub</span>
    </div>
    <div class="technology-tag">
      <img
        src="/src/assets/wordpress_logo.svg"
        alt="Vue.js logo"
        class="tech-logo"
      />
      <span>WordPress</span>
    </div>
    <div class="technology-tag">
      <img src="/src/assets/database.svg" alt="Vue.js logo" class="tech-logo" />
      <span>Databases</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "Technologies",
};
</script>

<style scoped>
.titulo {
  color: rgb(31, 41, 58);
  text-align: center;
  font-weight: bold;
  font-size: 18px;
  margin-top: 70px;
}

.technologies {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-top: 30px;
  margin-bottom: 90px;
}

.technology-tag {
  display: flex;
  align-items: center;
  gap: 8px;
  background-color: #e0f2fe;
  color: #1f293a;
  padding: 8px 16px;
  border-radius: 9999px;
  font-weight: 500;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05);
}

.tech-logo {
  width: 20px;
  height: 20px;
}
.technology-tag:nth-child(1) {
  background-color: #aeecd0; /* Verde Vue.js */
}

.technology-tag:nth-child(2) {
  background-color: #a9adf2; /* Azul Vite */
}

.technology-tag:nth-child(3) {
  background-color: #d8a090; /* Laranja HTML */
}

.technology-tag:nth-child(4) {
  background-color: #96c1dd; /* Azul CSS */
}

.technology-tag:nth-child(5) {
  background-color: #fcf3aa; /* Amarelo JS */
}

.technology-tag:nth-child(6) {
  background-color: #a0a0a0; /* Preto GitHub */
}

.technology-tag:nth-child(7) {
  background-color: #a0a0a0; /* Preto WordPress */
}

.technology-tag:nth-child(8) {
  background-color: #9ff6b9; /* Verde Databases */
}
</style>
