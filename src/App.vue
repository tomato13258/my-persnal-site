<script setup>
import { RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header class="w-100 flex justify-center">
    <div class="w-[80%] py-[20px]  flex justify-center">
      <div class="w-[60%] header-img">
        <img class="w-[30%] stamp-img" src="./components/pictures/240323 Welcome-02.png" alt="">
        <img src="./components/pictures/230706aa.jpg" alt="我的作品">
      </div>
    </div>

  </header>
  <nav class="py-[10px] w-100 flex justify-center">
    <div class="w-[80%] border-y-[3px] border-black">
      <div class="py-[15px] flex justify-center text-[20px] gap-[30px] tracking-widest">
        <button class="nav-btn">
          <span class="mb-[5px]">ABOUT</span>
        </button>
        <button class="nav-btn">
          <span>WORK</span>
        </button>
        <button class="nav-btn">
          <span>ARTICAL</span>
        </button>
        <button class="nav-btn">
          <span>CONTACT</span>
        </button>
      </div>
    </div>
  </nav>
  <RouterView />
  <footer>
    <div class="w-100 h-[100px] bg-cyan-300">
      Illustration by <a href="https://icons8.com/illustrations/author/RogqKjMRAQ79">xopolin</a> from <a href="https://icons8.com/illustrations">Ouch!</a>
    </div>
  </footer>
</template>

<style scoped>
.header-img {
  position: relative;
  pointer-events: none;
}

.stamp-img {
  position: absolute;
  right: -20px;
  bottom: 60px;
  transform: rotate(15deg);
}

.nav-btn {
  position: relative;
  overflow: hidden;
  padding: 0 0 5px 0;
}
.nav-btn:hover {
 color: #9d5353;
}

.nav-btn::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 2.5px;
  border-radius: 20px;
  color: #9d5353;
  background-color: currentColor;
  transform: scaleX(0);
  transform-origin: center;
  /* 這裡可以變成從中間產生動畫 */
  transition: transform 0.2s ease-out;
}

.nav-btn:hover::after {
  transform: scaleX(1);
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
