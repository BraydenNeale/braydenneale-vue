<template>
    <div>
        <slot></slot>
    </div>
</template>

<style scoped>
div {
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  padding: 0.5rem;
  margin: 1rem auto;
  max-width: 40rem;
}

div:hover,
div:active {
    box-shadow: 5px 10px 20px rgba(0, 0, 0, 0.26);
}
</style>