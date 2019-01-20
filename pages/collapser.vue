<template>
  <div class="expander">
    <a
      class="expander-link"
      @click="collapsed = !collapsed"
    >{{collapsed ? expandText : collapseText }}</a>
    <slot v-if="!collapsed"></slot>
  </div>
</template>

<script>
export default {
  props: {
    expandText: String,
    collapseText: String
  },
  data() {
    return {
      collapsed: true
    }
  }
}
</script>