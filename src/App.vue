<template>
  <div id="app">
    <v-header></v-header>
    <div class="tab">
      i am tab!
    </div>
    <div class="content">
      i am content!
    </div>
  </div>
</template>

<script>
  import header from '@/components/header/header';

  export default {
    components: {
      'v-header': header
    }
  };
</script>

<style>
</style>
