<template>
  <div>
    <div class="logo">
       <img width=200 src="https://www.baselhack.ch/images/app/logos/baselhack_white.png"/>
    </div>
    <nav>
      <ul>
        <li>
          <NuxtLink to="/">Mountains</NuxtLink>
        </li>
      </ul>
    </nav>
    <main>
      
      <slot />
    </main>
  </div>
</template>

<style>
:root {
  --primary-color: #00c58e;
}

body {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
    Helvetica Neue, Arial, Noto Sans, sans-serif, Apple Color Emoji,
    Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
  margin: 0;
  background-color: black;
  color: white;
}

a {
  color: inherit;
  text-decoration: none;
}
nav a:hover {
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

main {
  margin: 0 auto;
  margin-top: 100px;
  padding: 0 1rem;
  max-width: 1280px;
  text-align: center;
}

img {
  margin-bottom: 1rem;
}

ul {
  list-style-type: none;
  padding: 0;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
li {
  margin: 0 0.5rem;
  padding: 0.25rem;
  font-size: 1.2rem;
}

nav {
  padding: 0 1rem;
}

nav li {
  color: cyan;
  text-decoration: underline;
}

a.nuxt-link-exact-active {
  color: #00c58e;
}

.logo {
  width: 100%;
  text-align: center;
}

.logo img {
  padding: 30px;
  max-width: 200px;
}
</style>
