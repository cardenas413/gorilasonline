<template>
  <div id="app">
    <Navigator/>
    <router-view/>
  </div>
</template>

<style lang="scss">

</style>
<script>
  import Navigator from "./components/Partials/Navigator";
  export default {
    components: {Navigator}
  }
</script>