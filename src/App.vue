<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Personal from './components/Personal.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="shadow mb-1 bg-body rounded" src="@/assets/nathan.jpg" width="225" height="225" border-radius="20" />
    <div class="wrapper">
      <Personal />
      <Menu />
      <!-- <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav> -->

    </div>
  </header>

  <RouterView />
</template>

<style scoped>
.card{
  box-shadow: 0 .5rem 1rem rgba(black, .15);
}

header {
  line-height: 1.5;
  max-height: 100vh;
}


nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  /* padding: 0 1rem;  */
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    /* place-items: center; */
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    /* display: flex; */
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
