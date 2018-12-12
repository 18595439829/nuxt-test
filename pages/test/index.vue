<template>
  <div>
    test的index
    <nuxt-link :to="{name: 'test-home'}">test-home</nuxt-link>
    <!-- <nuxt-link :to="{name: 'test-about'}">test-about</nuxt-link> -->
    <!-- <nuxt-link :to="{name: 'test-text'}">test-about</nuxt-link> -->
    <div>
      <nuxt-child/>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
