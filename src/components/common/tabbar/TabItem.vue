<template>
  <div class="tab-item">
      <div class="tab-top"><slot name='img'></slot></div>
      <div><slot name='text'></slot></div> 
  </div>
</template>

<script>
export default {
    name:"TabItem"
}
</script>

<style>
.tab-item{ 
    flex: 1; 
    text-align: center;
    font-size: 10px;
    font-weight: bold;
    text-align: center;
}
.tab-item img{
    width: 20px;
    height: 20px;
    margin-top:3px;
}
.tab-botton{
 
}
</style>