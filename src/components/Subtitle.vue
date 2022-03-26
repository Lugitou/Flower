<template>
  <div class="subtitle">
    <h1>FullStack Developer</h1>
    <h1>From <span>Paris</span></h1>
  </div>
</template>

<script>
export default {
  name: 'Subtitle',
};
</script>

<style lang="scss" scoped>
.subtitle {
  position: absolute;
  bottom: 50px;
  left: 50px;

  animation: textFadeInLeft 0.75s ease-in-out;

  h1 {
    font-family: 'Montserrat';
    font-size: 1.75rem;
    font-weight: 700;

    &:nth-child(2) {
      font-weight: 400;
      font-size: 1.5rem;
    }
  }

  span {
    color: red;
  }
}
</style>
