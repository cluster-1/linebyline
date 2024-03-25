<template>
  <div>
    <GAHeader></GAHeader>
    <div class="main-wrapper bg-white-green">
      <div class="container">
        <div class="story-section write-story bg-white">
          <div class="s-left">
            <h3 class="alt-title">PROMPT 1</h3>
            <h2 class="main-title">Essentials Only</h2>
          </div>
          <div class="s-right">
            <p class="desc">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
              reprehenderit in voluptate velit esse cillum dolore eu fugiat
              nulla pariatur. Excepteur sint occaecat cupidatat non proident,
              sunt in culpa qui officia deserunt mollit anim id est laborum.
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
              reprehenderit in voluptate velit esse cillum dolore eu fugiat
              nulla pariatur.
            </p>
            <div class="button-text-wrap">
              <div class="main-btn">
                <button>Post</button>
              </div>
              <a @click="openSideMenu"> Community Guidelines</a>
            </div>
          </div>
          <div class="story-close-icon">
            <svg
              width="19"
              height="19"
              viewBox="0 0 19 19"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path d="M1 1L18.5 18.5" stroke="#9A9A9A" />
              <path d="M1 18.5L18.5 0.999999" stroke="#9A9A9A" />
            </svg>
          </div>
        </div>
      </div>
      <GAFooter></GAFooter>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return { menuOpen: true };
  },
  methods: {
    openSideMenu() {
      this.menuOpen = !this.menuOpen;
      this.$bus.$emit("openSideMenuEvent", { open: this.menuOpen });
    },
  },
};
</script>
