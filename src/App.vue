<template>
  <div>
    <HeaderVue/>
    <div class="wrap">
      <MenuVue/>
      <ContentVue/>
    </div>
  </div>
</template>

<script>
import HeaderVue from "./components/HeaderVue.vue"
import MenuVue from "./components/MenuVue.vue"
import ContentVue from "@/components/ContentVue.vue"

export default {
  name: 'App',
  components: {
    HeaderVue,
    MenuVue,
    ContentVue,
  }
}
</script>

<style scoped>
.wrap {
  display: flex;
}
</style>
