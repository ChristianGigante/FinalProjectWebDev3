<template>
  <div >
    <b-card v-for="(element, i) in groups" :key="i" img-src="element.images" img-alt="element.name" img-left class="mb-3">
      <b-card-text>element.motto</b-card-text>
    </b-card>
  </div>
</template>

<script>
export default {
  data() {
    return {
      groups: [
        {
          images: "../assets/img1.png",
          name: "Christian Gigante",
          position: "a",
          motto:
            "First, have a definite, clear practical ideal; a goal, an objective. Second, have the necessary means to achieve your ends; wisdom, money, materials, and methods. Third, adjust all your means to that end. ~ Aristotle "
        },
        {
          images: "../assets/img1.png",
          name: "Chilla Jean Cabungcag",
          position: "a",
          motto:
            "Let our advance worrying become advance thinking and planning. ~ Winston Churchill"
        },
        {
          images: "../assets/img1.png",
          name: "Marion Jay Balugo",
          position: "a",
          motto:
            "Plans are worthless. Planning is essential. ~ Dwight D. Eisenhower "
        },
        {
          images: "../assets/img1.png",
          name: "Hannah Mae Peliño",
          position: "a",
          motto:
            "A good plan can help with risk analyses but it will never guarantee the smooth running of the project.  ~ Bentley and Borman"
        }
      ]
    };
  }
};
</script>

<style scoped>
</style>