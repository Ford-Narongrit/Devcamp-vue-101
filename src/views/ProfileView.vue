<template>
  <div>
    <profile-card
      name="JobJob"
      work="at CNC2"
      birthday="25 September 2024"
      content="KU99"
    ></profile-card>
    <profile-card
      :image="image"
      :name="name"
      :work="work"
      :birthday="birthday"
      :content="content"
    ></profile-card>
  </div>
</template>

<script>
import profileCard from "../components/Profile.vue";
export default {
  data() {
    return {
      name: "Narongrit",
      birthday: "25 September 2022",
      work: "work at CNC",
      content: "KU79",
      image: "../assets/images/profile.jpg",
    };
  },
  components: {
    profileCard,
  },
};
</script>

<style></style>
