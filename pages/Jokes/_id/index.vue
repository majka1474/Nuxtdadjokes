<template>
  <div>
    {{ $route.params.id }}
  </div>
</template>

<script>
import axios from "axiois"

export default {
  data() {
    return {
      joke: {}
    }
  }
}
</script>

<style>
  
</style>