<template>
  <!-- <div>
    <HeaderVue/>
    <div class="wrap">
      <MenuVue/>
      <ContentVue/>
    </div>
  </div> -->

  <div>
    <BoxVue color="blue"/>
    <BoxVue color="purple"/>
    <BoxVue color="green"/>
    <BoxVue color="blue"/>
    <BoxVue color="purple"/>
    <BoxVue/>
  </div>
</template>

<script>
// import HeaderVue from "./components/HeaderVue.vue"
// import MenuVue from "./components/MenuVue.vue"
// import ContentVue from "@/components/ContentVue.vue"
import BoxVue from "@/components/BoxVue.vue"

export default {
  name: 'App',
  components: {
    // HeaderVue,
    // MenuVue,
    // ContentVue,
    BoxVue,
  }
}
</script>

<style scoped>
.wrap {
  display: flex;
}
</style>
