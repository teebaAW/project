<script>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="navbar">
    <div class="left-side"><h1>CamScan</h1></div>
    <div class="right-side">
      <div><RouterLink class="navbar-item" to="/">Home</RouterLink></div>
      <!-- <div><RouterLink class="navbar-item">About</RouterLink></div> -->
      <!-- <div><RouterLink class="navbar-item">Contact Us</RouterLink></div> -->
    </div>
  </div>
</template>

<style>
.navbar {
  display: flex;
  justify-content: space-between;
  justify-items: center;
  gap: 5px;
  font-size: larger;
  color: black;
  background-color: #005ad5;
  padding-right: 100px;
  padding-top: 10px;
}

.navbar-item {
  text-decoration: none;
  font-size: larger;
  color: aliceblue;
  padding: 10px;
}

.navbar .right-side {
  display: flex;
}

.navbar .left-side {
  padding-left: 100px;
  color: aliceblue;
}
</style>
