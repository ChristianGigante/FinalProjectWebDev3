<template>
  <div>
    <b-card v-for="(element, i) in groups" :key="i" img-src="element.images" img-alt="element.name" img-left class="mb-3">
      <img v-bind:src="element.images" alt="" srcset="">
      <p>{{element.name}}</p>
      <b-card-text>{{ element.motto }}</b-card-text>
    </b-card>
  </div>
</template>

<script>
export default {
  props:["groups"],
  data() {
    return {
      
    };
  }
};
</script>

<style scoped>
</style>