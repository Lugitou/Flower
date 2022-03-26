<template>
  <div class="media">
    <a href="https://github.com/Lugitou">
      <img src="../assets/github.svg" alt="twitter" />
    </a>
    <a href="https://www.linkedin.com/in/louis-bellefemine/">
      <img src="../assets/linkedin.svg" alt="linkedin" />
    </a>
  </div>
</template>

<script>
export default {
  name: 'Media',
};
</script>

<style lang="scss" scoped>
.media {
  position: absolute;
  bottom: 50px;
  right: 50px;

  display: flex;
  align-items: center;
  gap: 2rem;

  animation: textFadeInRight 0.75s ease-in-out;

  a {
    img {
      filter: invert(100%) hue-rotate(357deg) brightness(100%) contrast(103%);
      width: 1.5rem;
      transition: transform 0.25s ease-in-out;
    }

    &:hover {
      img {
        filter: invert(33%) sepia(93%) saturate(7362%) hue-rotate(359deg) brightness(102%)
          contrast(130%);
        transform: translateY(-5px);
      }
    }
  }
}
</style>
