<template>
  <div class="alerta">
    <slot></slot>
  </div>
</template>

<style>
.alerta {
  text-align: center;
  margin-bottom: 2rem;
  color: #a2f818;
  background-color: rgb(224, 69, 69);
  text-transform: uppercase;
  font-weight: 700;
  font-size: 1.4rem;
  padding: 0.5rem;
}
</style>
