<!--
Theme 'geist' places all the text in image-left directly against the image.
So we use a custom layout to fix this.
-->
<script setup lang="ts">
import { computed } from 'vue'

const props = defineProps({
  image: { type: String, default: '' },
  class: { type: String, default: '' },
  backgroundSize: { type: String, default: 'cover' },
})

function resolveAssetUrl(url: string) {
  if (url.startsWith('/'))
    return import.meta.env.BASE_URL + url.slice(1)
  return url
}

const style = computed(() => props.image
  ? {
      backgroundImage: `url("${resolveAssetUrl(props.image)}")`,
      backgroundPosition: 'center',
      backgroundRepeat: 'no-repeat',
      backgroundSize: props.backgroundSize,
    }
  : {})
</script>

<template>
  <div class="grid grid-cols-2 w-full h-full auto-rows-fr">
    <div class="w-full h-full" :style="style" />
    <div class="slidev-layout default slidev-content-col" :class="props.class">
      <slot />
    </div>
  </div>
</template>

<!-- geist doesn't pad the content column, so give it breathing room. -->
<style>
.slidev-content-col {
  padding: 2.5rem 3rem;
}
</style>
