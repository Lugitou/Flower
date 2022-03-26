<template>
  <Logo />
  <Name />
  <Flower />
  <Subtitle />
  <Media />
</template>

<script>
import Flower from './components/Flower/Flower.vue';
import Logo from './components/Logo.vue';
import Name from './components/Name.vue';
import Subtitle from './components/Subtitle.vue';
import Media from './components/Media.vue';

export default {
  name: 'App',
  components: {
    Flower,
    Logo,
    Name,
    Subtitle,
    Media,
  },
};
</script>

<style lang="scss">
html {
  background: $dark;
  color: white;
}
</style>
