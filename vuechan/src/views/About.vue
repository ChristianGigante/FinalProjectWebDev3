<template>
  <div class="about">
    <br />
    <h1>
      <center class="text-white">Developers</center>
    </h1>
    <ListOfDev v-bind:groups="groups" />
  </div>
</template>
<script>
import ListOfDev from "./ListOfDev";
export default {
  components: {
    ListOfDev
  },
  data() {
    return {
      groups: [
        {
          pic: require("@/assets/img2.jpg"),
          name: "Christian Gigante",
          position: "Project Manager",
          motto:
            "First, have a definite, clear practical ideal; a goal, an objective. Second, have the necessary means to achieve your ends; wisdom, money, materials, and methods. Third, adjust all your means to that end. ~ Aristotle "
        },
        {
          pic: require("@/assets/img3.png"),
          name: "Chilla Jean Cabungcag",
          position: "Backend Developer",
          motto:
            "Let our advance worrying become advance thinking and planning. ~ Winston Churchill"
        },
        {
          pic: require("@/assets/img2.jpg"),
          name: "Marion Jay Balugo",
          position: "Frontend Developer",
          motto:
            "Plans are worthless. Planning is essential. ~ Dwight D. Eisenhower "
        },
        {
          pic: require("@/assets/img3.png"),
          name: "Hannah Mae Peliño",
          position: "Frontend Developer",
          motto:
            "A good plan can help with risk analyses but it will never guarantee the smooth running of the project.  ~ Bentley and Borman"
        }
      ]
    };
  }
};
</script>
