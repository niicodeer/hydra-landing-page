<script setup>
import logo from "../../public/hydra-logo.png";
import Button from "./Button.vue";
</script>
<template>
  <header>
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img :src="logo" alt="logo" width="100%" height="auto" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse d-flex justify-content-end"
          id="navbarNav"
        >
          <ul
            class="navbar-nav d-flex flex-fill justify-content-between margin"
          >
            <li class="nav-item">
              <a class="nav-link" href="#">ABOUT</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SERVICES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">TECHNOLOGIES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">HOW TO</a>
            </li>
          </ul>
          <div class="d-flex gap-4">
            <Button buttonText="CONTACT US" secondary />
            <Button buttonText="JOIN HYDRA" />
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>
<style scoped>
a {
  color: white;
  font-weight: bold;
  font-size: 12px;
}
.margin {
  margin: 0 144px;
}
</style>
