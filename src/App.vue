  <template>
  <div id="app">
    <Header></Header>
    <AppBody></AppBody>
    <VueSidebarMenu></VueSidebarMenu>
  </div>
</template>

  <script>
  import Header from "components/frame/Header.vue";
  import AppBody from 'components/frame/Body.vue';

  import VueSidebarMenu from 'vue-sidebar-menu'


  export default {
    name: "app",
    components: {
      Header,
      AppBody,
      VueSidebarMenu
    }
  };
  </script>

