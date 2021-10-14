<template>
  <div class="about">
    <div class="cuadro verde">
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum porro
        ducimus voluptates dolores ullam nulla nisi consectetur maxime impedit
        asperiores, debitis sequi, iste, architecto possimus eos dolore
        pariatur! Voluptas, perspiciatis!
      </p>
    </div>
    <div class="cuadro azul">
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eum porro
        ducimus voluptates dolores ullam nulla nisi consectetur maxime impedit
        asperiores, debitis sequi, iste, architecto possimus eos dolore
        pariatur! Voluptas, perspiciatis!
      </p>
    </div>
  </div>
</template>

<style scoped>
.about {
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding: 1rem 0.5rem;
  background-color: lightyellow;
}

.cuadro {
  padding: 2rem;
  border: 1px solid gray;
  border-radius: 3px;
  width: 300px;
}

.verde {
  background: rgb(177, 248, 177);
}

.azul {
  background: rgb(132, 135, 175);
}

@media only screen and (max-width: 600px) {
  .about {
    background-color: lightblue;
    flex-direction: column;
    align-items: center;
  }

  .cuadro {
    width: 200px;
  }
}
</style>