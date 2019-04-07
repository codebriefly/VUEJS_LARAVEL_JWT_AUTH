<template>
    <div id="main">
        <header id="header">
            <Menu></Menu>
        </header>
        <div id="content">
            <router-view></router-view>
        </div>
    </div>
</template>
<script>
  import Menu from './components/Menu.vue'
  export default {
    data() {
      return {
        //
      }
    },
    components: {
      Menu
    }
  }
</script>