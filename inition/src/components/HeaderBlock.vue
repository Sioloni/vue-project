<template>
  <header class="header">
    <!-- <img src="../assets/logo.png" alt="Your image" /> -->
    <div>
      <h1>YOUR GUIDE TO THE SPIRITUAL WORLD</h1>
    </div>
  </header>
  <nav class="tabs">
    <a href="#" class="tab">About me</a>
    <a href="#" class="tab">Services</a>
    <a href="#" class="tab">Events</a>
    <a href="#" class="tab">Online record</a>
  </nav>
</template>

<script>
export default {
  name: "HeaderBlock",
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

.header {
  width: 1000px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding-top: 30px;
}

.header img {
  width: 200px;
  height: 200px;
}

.header h1 {
  font-size: 31px;
  color: #bc8aac;
}

.tabs {
  padding-top: 10px;
  display: flex;
  border-top: 2px solid #bc8aac;
  overflow-x: auto;
  justify-content: center;
}

.tab {
  padding: 10px 20px;
  color: #bc8aac;
  text-decoration: none;
}

.tab:last-child {
  border-right: none;
}

@media screen and (max-width: 768px) {
  .header {
    flex-direction: column;
    align-items: flex-start;
    padding: 10px;
  }

  .header img {
    margin-right: 0;
    margin-bottom: 10px;
  }

  .header h1 {
    position: relative;
  }

  .tabs {
    flex-wrap: wrap;
  }

  .tab {
    width: 50%;
    border-right: none;
  }

  .tab:last-child {
    border-bottom: none;
  }
}
</style>
