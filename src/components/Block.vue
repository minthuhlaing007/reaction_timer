<template>
  <div class="block">
    Click {{ delay }}
  </div>
</template>

<script>
export default {
props:["delay"],
}
</script>

<style>
.block{
  width: 300px;
  height: 300px;
  padding: 20px;
  margin: 50px auto;
  background: #2c3e50;
  color:white
}
</style>