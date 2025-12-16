<template>
  <header class="header">
    <img
      src="/src/assets/logo.png"
      alt="Memes do Camões"
      class="logo"
    />    
        <p>A página onde o sarcasmo é património cultural.</p>
  </header>
</template>

<script setup>
</script>
<style>
  .logo {
    width: 30%;     /* desktop */
    max-width: 80%;
    height: auto;
    margin-bottom: 24px;
  }

/* MOBILE */
@media (max-width: 768px) {
  .logo {
    width: 300px;   /* 👈 maior no mobile */
    max-width: 90%;
  }
}

/* MOBILE PEQUENO */
@media (max-width: 480px) {
  .logo {
    width: 280px;
  }
}

</style>