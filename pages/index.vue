<template>
  <div>
    <h1>A Start</h1>
    <g-btn style="margin: 12px;" class="btn--secondary btn--raised" @click="doThis">Hello</g-btn>
  </div>
</template>

<script>

export default {
  methods: {
    doThis() {
      console.log('hello')
    }
  },
}
</script>
