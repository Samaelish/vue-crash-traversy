<script>
export default {
  data() {
    return {
      name: 'John Doe',
      status: true
    }
  }
}
</script>

<template>
  <h1>Hello {{ name }}</h1>
  <p v-if="status">User whouser</p>
</template>