<template>
  <main class="main">
    <div class="main-block">
      <div class="main-text">
        <h1>About me</h1>
        <h3>My name is Elena</h3>
        <p>
          My mission is to help people:<br />
          - realize your spiritual nature,<br />
          - find harmony with yourself and with the world around you,<br />
          - realize your creative potential,<br />
          - find your purpose <br />
          - find solutions to your problems and problems<br />
          Together with me you will be able to direct your life in the
          direction<br />
          of development and harmony!
        </p>
      </div>
    </div>
    <div class="main-img">
      <img src="../assets/image.jpg" alt="" />
    </div>
  </main>
</template>

<script>
export default {
  name: "MainBlock",
  data() {
    return {};
  },
};
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
}

.main {
  margin-top: 40px;
  border: 1px solid black;
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
}

.main-text {
  padding-left: 20px;
  color: #b48caa;
}

img {
  width: 400px;
  height: 400px;
}

h1 {
  font-size: 56px;
}

h3 {
  font-size: 26px;
}

p {
  font-size: 18px;
}
</style>
