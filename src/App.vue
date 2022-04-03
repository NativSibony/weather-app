<script setup>
import SunAndCloud from "./components/SunAndCloud.vue";
import CurrentDay from "./components/CurrentDay/CurrentDay.vue";
const apiKey = import.meta.env.VITE_API_KEY;
</script>

<template>
  <main>
    <section>
      <CurrentDay />
    </section>
    <section>
      <SunAndCloud />
    </section>
  </main>
</template>

<style>
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  height: 100vh;
  width: 100vw;
  font-family: "Poppins", sans-serif;
  color: #333;
}

html {
  background: linear-gradient(200deg, #def4f8, rgba(255, 0, 0, 0) 40.71%),
    linear-gradient(127deg, #fdfdfd, rgba(0, 255, 0, 0) 90.71%),
    linear-gradient(336deg, #dad9bb, rgba(0, 0, 255, 0) 100.71%);
}

main {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap-reverse;
}

main > * {
  flex: 1 1 40em;
}

section {
  display: flex;
  place-items: center;
  justify-content: center;
}
</style>
