<template>
  <div class="home">
    <ResponsiveNav msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import ResponsiveNav from '@/components/ResponsiveNav.vue'

export default {
  name: 'Home',
  components: {
    ResponsiveNav
  }
}
</script>
