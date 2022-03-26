<template>
  <div class="logo">
    <img src="../assets/rose.svg" alt="Rose" />
    <h1>ROSE</h1>
  </div>
</template>

<script>
export default {
  name: 'Logo',
};
</script>

<style lang="scss" scoped>
.logo {
  display: flex;
  align-items: center;
  gap: 1rem;

  position: absolute;
  top: 50px;
  left: 50px;

  animation: textFadeInLeft 0.75s ease-in-out;

  img {
    width: 2.5rem;
  }

  h1 {
    font-family: 'Montserrat Alternates';
    font-size: 1.75rem;
    font-weight: 100;
  }
}
</style>
