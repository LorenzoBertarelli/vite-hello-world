<script>
import AppJumbo from './components/AppJumbo.vue';

export default {
  components: {
    AppJumbo
  },
  data() {
    return {
      title: "La mia prima app con Vite!"
    }
  }
}
</script>

<template>
<h1>{{ title }}</h1>
<AppJumbo></AppJumbo>
</template>

<style>
h1 {
  color: rgb(202, 1, 1);
  text-align: center;
}
</style>
