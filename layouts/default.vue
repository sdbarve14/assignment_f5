<template>
<div>
    <header class="sticky top-0 z-30 bg-white drop-shadow-md">
    <NavigationBar @base-slide-panel="showMenu = true" class="w-full"></NavigationBar>
  </header>
    <div>
    <slot />
  </div>
</div>
    
  
  
  
</template>

<script>

</script>

<style scoped>

</style>