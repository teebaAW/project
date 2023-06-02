<script>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <div class="navbar">
    <div class="left-side"><h1>CamScan</h1></div>
    <div class="right-side">
      <RouterLink class="navbar-item" to="/">Home</RouterLink>
      <RouterLink class="navbar-item" to="/">About</RouterLink>
      <RouterLink class="navbar-item" to="/">Contact Us</RouterLink>
    </div>
  </div>
</template>

<style>
/*.navbar {
  display: flex;
  justify-content: space-between;
  justify-items: center;
  gap: 5px;
  font-size: larger;
  color: black;
  background-color: #005ad5;
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

*/
.navbar {
  padding: 10px;
  display: flex;
  justify-content: space-between;
  justify-items: center;
  font-size: x-small;
  gap: 5px;
  color: black;
  background-color: #005ad5;
}

.navbar-item {
  text-decoration: none;
  font-size: larger;
  color: aliceblue;
  padding: 10px;
}

.navbar .right-side {
  display: flex;
  justify-content: center;
  justify-items: center;
}

.navbar .left-side {
  color: aliceblue;
  font-size: 10px;
}

@media screen and (min-width: 280px) and (max-width: 374px) {
  .navbar {
    padding: 6px;
    gap: 3px;
    font-size: 5px;
    color: black;
  }

  .navbar-item {
    font-size: 10px;
    padding: 10px;
  }

  .navbar .left-side {
    font-size: 10px;
  }
}

@media screen and (min-width: 640px) {
  .navbar {
    font-size: small;
  }
  .navbar-item {
    font-size: 18px;
    padding: 10px;
  }
  .navbar .left-side {
    font-size: 20px;
  }
}
</style>
