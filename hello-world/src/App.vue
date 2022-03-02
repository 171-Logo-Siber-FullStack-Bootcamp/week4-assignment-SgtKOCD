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
    <a class="scroll-to-top rounded" href="#page-top">
      <i class="fas fa-angle-up"></i>
    </a>
    <LogOut />
  </div>
</template>

<script>
import SideBar from "./components/SideBar/SideBar.vue";
import TopBar from "./components/TopBar/TopBar.vue";
import LogOut from "./components/LogOut/LogOut.vue";
export default {
  name: "App",

  components: {
    SideBar,
    TopBar,
    LogOut,
  },
};
</script>

<style>
</style>
