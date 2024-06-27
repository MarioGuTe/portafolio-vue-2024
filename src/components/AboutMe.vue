<template>
  <div class="about-me">
    <h3>Acerca de mí</h3>
    <p class="paragraph">
      Hola soy Mario, Desarrollador Fullstack además de Músico Profesional de
      basta experiencia, he desarrollado distintos proyectos de manera
      freelance, independiente y autónoma donde he implementado soluciones tanto
      a funcionalidades de Frontend como la interacción del cliente con la
      interfaz de usuario aplicando distintas tecnologías como JavaScript,
      React, HTML, CSS.
    </p>
    <p class="paragraph">
      Soy una persona constante, responsable y sobre todo apasionada por
      aprender nuevas tecnologías, aptitudes que me han permitido explorar con
      profundidad diferentes desafios personales y de igual manera me han
      permitido enfocar mis esfuerzos en comprender y buscar las mejores
      soluciones para el cliente.
    </p>
  </div>
</template>

<style scoped>
.about-me {
  background-color: #7c3aed;
  width: 100%;
  text-align: center;
  padding: 3rem 1rem;
  color: white;
}

.about-me h3 {
  font-size: 1.5rem;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  font-weight: bold;
}

.paragraph {
  font-size: 1rem;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  line-height: 2rem;
  font-weight: 500;
  max-width: 40rem;
  margin-left: auto;
  margin-right: auto;
}

@media (min-width: 1024px) {
  .paragraph {
    font-size: 1.25rem;
    padding-top: 1.5rem;
    padding-bottom: 1.5rem;
  }
}
</style>
