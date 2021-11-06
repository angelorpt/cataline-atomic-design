<template>
  <div class="component">
    <Logo />
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import { Logo } from '@/components/atoms'

export default defineComponent({
  components: {
    Logo
  }
})
</script>

<style lang="scss" scoped>
.component {
  width: 300px;
}
</style>
