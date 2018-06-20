<template>
  <div class="header" @click="logoClick">
    <Logo></Logo>
  </div>
</template>


<script>
import Logo from './logo.vue'
export default {
  name: 'Header',
  components: {
    Logo
  },
  methods: {
    logoClick () {
      console.log('clicked')
    }
  }
}
</script>

<style scoped lang="scss">
  .header {
    padding: 20px;
    border-bottom: 1px solid #cecece;
  }
</style>
