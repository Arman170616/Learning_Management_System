<template>
<div>
  <NavComponents/>

  <router-view/>

  <FooterComponents/>
</div>
</template>

<script>
import FooterComponents from '@/components/FooterComponents'
import NavComponents from '@/components/NavComponents'

export default {
  name: 'App',
  components: {
    NavComponents,
    FooterComponents
  }
}
</script>

<style lang="scss">
@import '../node_modules/bulma';
</style>
