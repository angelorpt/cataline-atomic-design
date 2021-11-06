<template>
  <div class="component">
    <NavBar />
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import { NavBar } from '@/components/molecules'

export default defineComponent({
  components: {
    NavBar
  }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 0;
}
</style>
