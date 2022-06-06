<template>
  <div class="content">
    <FadeTransition :duration="700" mode="out-in">
      <!-- your content here -->
      <nuxt></nuxt>
    </FadeTransition>
  </div>
</template>
<script>
import { FadeTransition } from 'vue2-transitions';
export default {
  components: {
    FadeTransition
  }
};
</script>
<style></style>
