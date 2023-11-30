<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div>
    <header>
      <nav class="container">
        <div class="branding">
          <h1>WeMake</h1>
        </div>
        <ul class="nav-routes">
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
        </ul>
      </nav>
    </header>
  </div>
</template>

<style lang="scss" scoped>
header {
  background-color: #c8c2c2;
  color: #21568c;
  nav {
    display: flex;
    align-items: center;
    padding: 25px 16px;

    .branding {
      display: flex;
      align-items: center;
      gap: 8px;
      img {
        max-width: 50px;
      }

      h1 {
        font-size: 24px;
      }
    }

    .nav-routes {
      display: flex;
      flex: 1;
      justify-content: flex-end;
      gap: 12px;
      list-style: none;

      a {
        text-decoration: none;
        color: inherit;
      }
    }
  }
}
</style>
