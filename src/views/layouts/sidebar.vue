<template>
  <div class="sidebar" id="sidebar">
    <div class="sidebar-inner slimscroll">
      <perfect-scrollbar class="scroll-area" :settings="settings" @ps-scroll-y="scrollHanle">
        <div id="sidebar-menu" class="sidebar-menu">
          <sidebar-item></sidebar-item>
          <div class="logout-btn">
            <router-link to="/"><span class="menu-side"><img src="@/assets/img/icons/logout.svg" alt="" /></span>
              <span>Logout</span></router-link>
          </div>
        </div>
      </perfect-scrollbar>
    </div>
  </div>
</template>

<script>
import { PerfectScrollbar } from "vue3-perfect-scrollbar";
import "vue3-perfect-scrollbar/dist/vue3-perfect-scrollbar.css";
export default {
  components: {
    PerfectScrollbar,
  },
  data() {
    return {
      settings: {
        suppressScrollX: true,
      },
    };
  },
  methods: {
    scrollHanle(evt) { },
    
  },
  
};
</script>
