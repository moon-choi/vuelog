<template>
  <h5> {{ posts[0].title }} </h5>
  <p>{{ posts[0].date }}</p>
</template>

<script>
export default {
  props: {
    posts: Array,
  }
}
</script>

<style></style>