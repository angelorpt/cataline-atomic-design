<template>
  <div class="component">
    <Header />
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import { Header } from '@/components/organisms'

export default defineComponent({
  components: {
    Header
  }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
