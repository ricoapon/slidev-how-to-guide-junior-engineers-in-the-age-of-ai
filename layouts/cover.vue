<!--
Theme 'geist' overrides the cover, which does not support using a background image.
So we just use our own cover layout to fix this.
-->
<script setup>
defineProps({ background: String })
</script>

<template>
  <div
    class="slidev-layout cover"
    :style="background && { backgroundImage: `linear-gradient(#0009, #0009), url(${background})` }"
  >
    <slot />
  </div>
</template>

<style>
.slidev-layout.cover {
  position: absolute;
  inset: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 3rem;
  color: #fff;
  background-size: cover;
  background-position: center;
}
</style>
