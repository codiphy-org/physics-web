<template>
  <div ref="text">
    <slot></slot>
  </div>
</template>

<script>
export default {
  methods: {
    renderMath() {
      window.MathJax.Hub.Queue([
        "Typeset",
        window.MathJax.Hub,
        this.$refs.text,
      ]);
    },
  },
  mounted() {
    this.renderMath();
  },
};
</script>
