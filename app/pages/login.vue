<script setup>
useHead({
  title: 'Login - Decolonialidade',
  meta: [
    { name: 'description', content: 'Sociologia, numa perspectiva de Modernidade e Colonialidade' },
  ],
})
</script>
<template>
  <div class='main' >
    <img src='/img/bg-deco.png'>
  </div>
  <div class='content'>
    <div class='square'>
      <h3>Faça login para mais</h3>
      <h1>Decolonialidade</h1>

      <input type='text' class='email' />
      <input type='text' class='email' />
      <div class='button'>Login</div>
      <div class='divider'></div>
      <div class='ou'>ou</div>
      <div class='button-two'>Inscreva-se</div>
    </div>
  </div>
</template>
<style scoped>
.main img{
  height: 100vh;
  width: 100%;
  object-fit: cover;
  position: absolute;
  filter: brightness(50%) contrast(1) blur(1.5px);
}
.content {
  display: flex;
  align-items: center;
  justify-content: center;
}

.square {
  padding:  40px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background: #fff;
  height: 90%;
  width: 40%;
  border-radius: 4px;
}
.square h3 {
    font-weight: 500;
    font-family: 'Montserrat';
}
.square h1 {
  font-family: 'Righteous';
    font-weight: 100;
}
.email {
  width:100%;
  height: 35px;
  border-radius: 20px;
  margin-top: 25px;
  margin-bottom: 4%;
  padding: 0 20px;
  border: solid .1px #000;
  transition: all .3s linear;
}
.email:focus {
  border-radius: 6px;
  border: solid .1px #000;
}

.email:focus-visible {
  border: none;
}
.button {
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 8px;
  margin-top: 25px;
  height: 40px;
  width: 50%;
  background: blue;
  color: #fff;
  cursor: pointer;
  font-weight: 400;
  font-family: 'Righteous';
}
.button-two {
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 8px;
  margin-top: 25px;
  height: 40px;
  width: 60%;
  background: blue;
  cursor: pointer;
  color: #fff;
  font-weight: 400;
  font-family: 'Righteous';
}

.divider{
  width: 70%;
  margin-top: 45px;
  border-top: solid .6px #000;
}
.ou {
  width: 30px;
  text-align: center;
  position: relative;
  top: -13px;
  font-size: 1.3rem;
  background: #fff;
  z-index: 2;
}
</style>
