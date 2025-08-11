<template>
  <div class="container">
    <div class="text-block">
      <div class="name-line">
        <span class="name1">Afonso</span>
        <span class="name2">Carrasquinho</span>
      </div>
      <samp class="name3">Front-end Developer & Web Enthusiast</samp>
    </div>
    <img
      src="https://cdn.discordapp.com/attachments/1199824602327691375/1404085342017163365/152220916.png?ex=6899e7e0&is=68989660&hm=8892cd6b0af2f394a7b2a749fa735b5a26d1c9e3a1154f40839f4dd624e79171"
      alt="Afonso Carrasquinho"
    />
  </div>
</template>

<script>
export default {
  name: "Intro",
};
</script>
<style scoped>
.container {
  height: 580px;
  width: 100%;
  background-color: rgb(241, 245, 251);
  padding-top: 2vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.name1 {
  color: rgb(59, 130, 246);
  font-weight: bold;
  font-size: 48px;
}
.name2 {
  color: rgb(31, 41, 55);
  font-weight: bold;
  font-size: 48px;
}
.name3 {
  color: rgb(75, 85, 99);
  margin-top: 17px;
  font-size: 17px;
}
.text-block {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin-left: 4.5vw;
}
.name-line {
  display: flex;
  gap: 8px;
}
img {
  width: 23%;
  margin-right: 80px;
  border-radius: 50%;
  border: 3px solid white;
  box-shadow: 0 3px 5px rgba(0, 0, 0, 0.3);
}
</style>
