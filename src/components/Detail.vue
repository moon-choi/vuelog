<template>
{{ $route.params.id }}
  <div>
    <h4>Detail page</h4>
    <h5>{{ posts[0].title }}</h5>
    <p>{{ posts[0].content }}</p>
  </div>
</template>

<script>
export default {
  props: {
    posts: Array,
  }

}
</script>

<style>

</style>