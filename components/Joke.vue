<template>
  <nuxt-link :to="'jokes/' + id">
    <div class="joke">
      <p>{{ joke }}</p>
    </div>
  </nuxt-link>
</template>

<script>
// scss読み込み
import "../assets/css/joke.scss";

export default {
  name: "Joke",
  props: ["joke", "id"]
};
</script>

<style>
</style>
