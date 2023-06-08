<template>
    <div>Header Component</div>
</template>

<script>
export default {};
</script>

<!-- scoped는 div style을 Header component로 한정시켜준다 -->
<style scoped>
div {
  position: sticky;
  height: 50px;
  border-bottom: 1px solid #ebebeb;
}
</style>