<template>
  <main class="main">
    <div class="main-block">
      <div class="main-text">
        <h1>About me</h1>
        <h3>My name is Elena</h3>
        <p>My mission is to help people:</p>
        <ul>
          <li>realize your spiritual nature,</li>
          <li>find harmony with yourself and with the world around you,</li>
          <li>realize your creative potential,</li>
          <li>find your purpose</li>
          <li>find solutions to your problems and problems</li>
          <li>Together with me you will be able to direct your life in the direction of development and harmony!</li>
        </ul>
        <div class="contacts">
          <a href=""><img src="../assets/facebook.svg" alt="facebook ico"></a>
          <a href=""><img src="../assets/twitter.svg" alt="twitter ico"></a>
          <a href=""><img src="../assets/linkedin.svg" alt="linkedin ico"></a>
          <a href=""><img src="../assets/instagram.svg" alt="instagram ico"></a>
        </div>
      </div>
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
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: Helvetica, sans-serif;
}


body {
  display: flex;
  justify-content: center;
}

.main {
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 40px;
}

.main-block {
  background: #fff;
  width: 90vw;
  padding-left: 40px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.main-text {
  color: #b48caa;
  width: 50vw;
}

.main-text > ul {
  list-style: ' - ';
  line-height: 30px;
  padding: 0;
  margin: 0;
}

.contacts {
  width: auto;
}

.contacts > a > img {
  width: 40px;
  padding: 10px 10px 0 0;
  transition: 200ms all;
}

.contacts > a > img:hover {
  opacity: 0.6;
}

img {
  width: 40%;
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
