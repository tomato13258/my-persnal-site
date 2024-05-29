<script setup>
import { RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="w-100 h-[500px] bg-slate-500"></div>
  </header>
  <nav>
    <div class="w-100 py-[15px] flex justify-center text-[20px] gap-[30px] tracking-widest bg-amber-300">
      <button class="nav-btn">
        <span class="mb-[5px]">ABOUT</span>
      </button>
      <button>
        <span>WORK</span>
      </button>
      <button>
        <span>ARTICAL</span>
      </button>
      <button>
        <span>CONTACT</span>
      </button>
    </div>
  </nav>
  <RouterView />
  <footer>
    <div class="w-100 h-[100px] bg-cyan-300"></div>
  </footer>
</template>

<style scoped>
.nav-btn{
  background-color: aliceblue;
  text-decoration: underline;
}
/* header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
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
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
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
} */
</style>
