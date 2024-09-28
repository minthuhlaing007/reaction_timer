<template>
    <p>Result is {{ score }}ms</p>
    <div v-if="score<300">
      <h1>You are too fast !!! Well Done...</h1>
    </div>
    <div v-else-if="score>250 && score<500">
      <h2>You are normal</h2>
    </div>
    <div v-else>
      <h3>You are too slow try again</h3>
    </div>
</template>

<script>
export default {
  props:["score"]
}
</script>

<style>

</style>