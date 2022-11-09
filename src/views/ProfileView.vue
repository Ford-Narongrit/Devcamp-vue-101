<template>
  <div class="flex items-center justify-center space-x-5 h-screen">
    <profile-card
      class="w-1/4"
      name="JobJob"
      work="at CNC2"
      birthday="25 September 2024"
      content="KU99"
    ></profile-card>
    <profile-card
      class="w-1/4"
      image="/assets/images/profile2.jpg"
      :name="name"
      :work="work"
      :birthday="birthday"
      :content="content"
    ></profile-card>
    <profile-card
      class="w-1/4"
      image="/assets/images/profile3.jpg"
      :name="name"
      :work="work"
      :birthday="birthday"
      :content="content"
    ></profile-card>
  </div>
</template>

<script>
import profileCard from "@/components/ProfileCard.vue";
export default {
  data() {
    return {
      name: "Narongrit",
      birthday: "25 September 2022",
      work: "work at CNC",
      content: "KU79",
      image: "/assets/images/profile.jpg",
    };
  },
  components: {
    profileCard,
  },
};
</script>

<style></style>
