<template>
  <div id="app">
    <h1>Blog Post Creator</h1>
    <blog-post-creator class="rteditor"></blog-post-creator>
  </div>
</template>

<script>
import BlogPostCreator from './components/BlogPostCreator.vue'

export default {
  name: 'app',
  components: {
    BlogPostCreator
  }
}
</script>

<style scoped>
h1 {
  margin-left: 20px;
  margin-top:10px;
}

.rteditor {
  margin-left: 20px;
  margin-right: 20px;
}
</style>
