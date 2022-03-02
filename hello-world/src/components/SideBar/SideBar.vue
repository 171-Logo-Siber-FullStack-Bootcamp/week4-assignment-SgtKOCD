<template>
  <div>
    <ul
      class="navbar-nav bg-gradient-primary sidebar sidebar-dark accordion"
      id="accordionSidebar"
    >
      <SidebarBrand />
      <NavitemDashboard />
      <NavMenu />
      <NavMenuUtilities />
      <NavCollapse />
      <NavCharts />
      <NavTables />

    </ul>
    
  </div>
</template>

<script>
import SidebarBrand from "./SidebarBrand.vue";
import NavitemDashboard from "./NavitemDashboard.vue";
import NavMenu from "./NavMenu.vue";
import NavMenuUtilities from "./NavMenuUtilities.vue";
import NavCollapse from "./NavCollapse.vue";
import NavCharts from './NavCharts.vue'
import NavTables from './NavTables.vue'

export default {
  name: "SideBar",
  components: {
    SidebarBrand,
    NavitemDashboard,
    NavMenu,
    NavMenuUtilities,
    NavCollapse,
    NavCharts,
    NavTables
  }
};
</script>

<style scoped>
</style>
