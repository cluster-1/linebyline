<template>
  <div>
    <NuxtPage />
    <div>
      <community v-show="openSideMenu"></community>
    </div>
  </div>
</template>
<script>
import community from "~/components/community.vue";
export default {
  components: { community },
  data() {
    return {
      openSideMenu: false,
    };
  },
  mounted() {
    var t = this;
    this.$bus.$on("openSideMenuEvent", function (data) {
      t.openSideMenu = data.open;
      console.log(data.open);
    });
  },
};
</script>
