<template>
  <section class="Home3">
    <div class="home-content3">
      <h1>Entre em contato comigo</h1>
    </div>
    <form id="forms"action="/enviar">
      <label for="nome">Nome:</label><br>
      <input type="text" id="nome" name="nome" required><br><br>
      <label for="email">E-mail:</label><br>
      <input type="email" id="email" name="email" required><br><br>
      <label for="mensagem">Mensagem:</label><br>
      <textarea id="mensagem" name="mensagem" rows="5" required></textarea><br><br>
      <button type="submit">Enviar</button>
    </form>
  </section>
</template>
<script setup>

</script>
<style>
.home-content3 h1 {
  font-size: 56px;
  font-weight: 700px;
  margin: -3px 0;
  color: #ffffff;
  text-align: center;
}
#forms {
  width: 100%;
  max-width: 500px;
  margin: 0 auto;
  padding: 20px;
}
</style>