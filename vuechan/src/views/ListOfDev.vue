<template>
  <div>
    <b-card v-for="(element, i) in groups" :key="i" :img-src="element.pic" :img-alt="element.name" img-left class="mb-3">
      <h3>{{element.name}}</h3>
      <h5>{{element.position}}</h5>
      <b-card-text>{{ element.motto }}</b-card-text>
    </b-card>
  </div>
</template>

<script>
export default {
  props:["groups"]
};
</script>

<style scoped>
</style>