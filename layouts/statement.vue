<template>
  <div class="slidev-layout statement">
    <div><slot /></div>
  </div>
</template>

<!-- geist doesn't style the statement layout, so vertically center it. -->
<style>
.slidev-layout.statement {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
  padding: 2rem 3rem;
}
</style>
