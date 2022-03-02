<template>
  <div>
    <div id="wrapper">
      <SideBar />
      <div id="content-wrapper" class="d-flex flex-column">
        <div id="content">
          <TopBar />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SideBar from "./components/SideBar/SideBar.vue";
import TopBar from "./components/TopBar/TopBar.vue";
export default {
  name: "App",

  components: {
    SideBar,
    TopBar
  },
};
</script>

<style>

</style>
