<script setup>
import HelloWorld from './components/HelloWorld.vue'



</script>

<template>
<div>
  <div class="welcome">
  <h2>Добро пожаловать на окно регистрации <br> lorem ipsum! </h2>
    <p>Пожалуйста, введите свои данные</p>
  </div>
  <form class="form" action="">
    <div class="form_div">
      <input  type="text" placeholder="Имя Пользователя">
      <input  placeholder="Почта" type="email">
      <input  placeholder="Пароль" type="password">
      <button>Зарегистрироваться</button>
    </div>
  </form>
</div>
</template>

<style scoped>
.welcome {
  margin-bottom: 300px;
  background:  #006b1b;
  padding: 20px;
  border-radius: 9px;
}

form {
  background-color: ;
  display: block;
  margin-top: 15px;
  width: 300px;
  margin-left: 100px;
  height: 150px;
}
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
