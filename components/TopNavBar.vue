<template>
<div>
  <topInfo/>
  <Menu/>
</div>
</template>

<script>
import topInfo from "@/components/layouts/topInfo";
import Menu from "@/components/layouts/Menu";

export default {
  name: "TopNavBar",
  components: {
    topInfo,Menu
  },
}
</script>

<style scoped>

</style>