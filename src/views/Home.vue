<template>
  <div>
    <hero />
    <!-- <home-content />
    <time-to-login /> -->
  </div>
</template>

<script>
import Hero from "../components/Hero";
import HomeContent from "../components/HomeContent";
import TimeToLogin from "../components/TimeToLogin";

export default {
  name: "home",
  components: {
    Hero,
    HomeContent,
    TimeToLogin
  }
};
</script>

<style lang="scss" scoped>
.next-steps {
  .fa-link {
    margin-right: 5px;
  }
}
</style>
