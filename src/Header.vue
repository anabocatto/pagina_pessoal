<template>
  <div class="foto">
    <img src="./assets/images/IMG_20250512_130817.jpg" alt="Minha Foto" />
  </div>
</template>

<style scoped>
.foto {
  text-align: center;
  margin-bottom: 1.5rem;
}
.foto img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid var(--rosa-claro);
}
@media (max-width: 600px) {
  .foto img {
    width: 120px;
    height: 120px;
  }
}
</style>
