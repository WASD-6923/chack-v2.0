<script setup>
import HelloWorld from './components/HelloWorld.vue'



</script>

<template>
<div>
  <div class="welcome">
  <h2>Добро пожаловать на окно регистрации <br> lorem ipsum! </h2>
    <p>Пожалуйста, введите свои данные</p>

  <form class="form" action="">
    <div class="form_div">
      <input class="input" type="text" placeholder="Имя Пользователя">
      <input class="input" placeholder="Почта" type="email">
      <input class="input" placeholder="Пароль" type="password">
      <button class="button">Зарегистрироваться</button>
    </div>
  </form>
</div>
</div>
</template>

<style scoped>
.button {
  margin-top: 15px;
  margin-left: 12px;
}
.welcome {

  margin-bottom: 300px;
  background:  #006b1b;
  padding: 20px;
  border-radius: 9px;
  max-width: 100%;
  width: 1000px;
  height: 700px;
}

form {
  background-color: #000000;
  margin-top: 100px;
  width: 350px;
  margin-left: 330px;
  height: 200px;
  border-radius: 9px;

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

.input {
  font-size: 15px;
  margin-left: 80px;
  margin-top: 30px;
  display: block;

}

.form_div {

  margin-top: 20px;
}
</style>
