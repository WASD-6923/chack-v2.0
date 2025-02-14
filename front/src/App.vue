<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div>
  
  <h2>Регистрация</h2>
  <form class="form" action="">
    <input  placeholder="Почта" type="email">
    <input  placeholder="Пароль" type="password">
    <button>Зарегистрироваться</button>
  </form>
</div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
