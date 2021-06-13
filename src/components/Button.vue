<template>
  <div>
    <header>
      <slot name="header"></slot>
    </header>
    <!-- <main> -->
    <slot>this is default </slot>
    <!-- </main> -->
    <footer>
      <slot name="footer"></slot>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>