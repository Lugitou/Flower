<template>
  <div class="name">
    <h1>Louis</h1>
    <h1>BELLEFEMINE</h1>
  </div>
</template>

<script>
export default {
  name: 'Name',
};
</script>

<style lang="scss" scoped>
.name {
  position: absolute;
  top: 50px;
  right: 50px;

  color: red;
  text-align: right;

  animation: textFadeInRight 0.75s ease-in-out;

  h1 {
    font-family: 'Montserrat';
    font-size: 1.75rem;
    font-weight: 400;

    &:nth-last-child(1) {
      font-weight: 700;
    }
  }
}
</style>
