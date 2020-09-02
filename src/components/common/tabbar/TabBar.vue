<template>
  <div class="tab-bar">
      <slot></slot>
  </div>
</template>

<script>
export default {
name:"TabBar"
}
</script>

<style>
.tab-bar{
    height: 49px;
    position: fixed;
    bottom: 0px;
    left: 0px;
    right: 0px;
    display: flex; 
}
</style>