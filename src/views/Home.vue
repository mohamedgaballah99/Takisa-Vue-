<template>
  <div class="home">
    <Tool></Tool>
    <Header></Header>
    <Feature></Feature>
     <Need></Need>
     <team></team>
     <trust></trust>
     <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Tool from "../components/Tool.vue";
import Header from "../components/Header.vue";
import Feature from "../components/Feature.vue";
import Need from "../components/Need.vue";
import team from "../components/team.vue";
import trust from "../components/trust.vue";
import Footer from "../components/footer.vue";

export default {
  name: "Home",
  components: {
    Tool,
    Header,
    Feature,
    Need,
    team,
    trust,
    Footer,
  }
};
</script>
<style lang="scss" scoped>
.home{
    background-image: url("../assets/images/bg.png");
    background-repeat: no-repeat;
    background-size: 100% 100%;
    background-position: center center;
}

</style>
