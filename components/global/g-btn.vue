<template functional>
  <button
    class="btn"
    :class="[data.staticClass, data.class]"
    :style="[data.staticStyle, data.style]"
    v-on="listeners"
  >
    <slot></slot>
  </button>
</template>

<script>
export default {
  
}
</script>
