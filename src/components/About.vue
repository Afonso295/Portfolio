<template>
  <div class="sobre">About Me</div>
  <div class="container">
    <div class="eu">
      <samp class="titulo">Who I Am</samp>
      <samp class="texto">
        <p>
          I'm a passionate web and mobile developer with a strong interest in
          creating engaging and functional digital experiences. My journey in
          tech started with a curiosity about how websites work, and has evolved
          into a professional path focused on front-end development.
          <br /><br />
          I particularly enjoy working with Vue.js and other modern frameworks
          that allow for building dynamic, responsive interfaces. When I'm not
          coding, I'm expanding my knowledge through online courses and building
          personal projects to test new skills.
        </p>
      </samp>
    </div>
    <div class="skills">
      <samp class="titulo">My Skills</samp>
      <ul class="skills-list">
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
        <li>Vue.js</li>
        <li>GitHub</li>
        <li>WordPress</li>
        <li>Image/Video Editing</li>
        <li>Computer Maintenance</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style scoped>
.sobre {
  font-size: 30px;
  font-weight: bold;
  text-align: center;
  margin-top: 70px;
  color: rgb(31, 41, 55);
}
.titulo {
  font-size: 20px;
  font-weight: bold;
  color: rgb(31, 41, 55);
  display: block;
  margin-bottom: 10px;
}
.texto {
  font-size: 17px;
  max-width: 46vw;
  display: flex;
  color: rgb(55, 65, 81);
  line-height: 1.6;
}

.container {
  display: flex;
  justify-content: space-around;
  gap: 40px;
  margin-top: 68px;
  flex-wrap: wrap;
}
.eu,
.skills {
  flex: 1;
  min-width: 300px;
  color: rgb(31, 41, 55);
}
.eu {
  margin-left: 62px;
}
.skills-list {
  display: grid;
  grid-template-columns: repeat(2, auto);
  gap: 8px 40px;
  list-style: none;
  padding: 0;
  margin: 0;
  color: rgb(31, 41, 55);
  line-height: 1.5;
}

.skills-list li {
  position: relative;
  padding-left: 20px;
}

.skills-list li::before {
  content: "•";
  position: absolute;
  left: 0;
  color: rgb(59, 130, 246);
  font-size: 20px;
  line-height: 1;
}
</style>
