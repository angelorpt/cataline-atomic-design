<template>
  <div class="component">
    <Service
      title="Teste"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto aliquam voluptates commodi, repudiandae fugit suscipit! Nam impedit nemo cumque quos atque. Dicta beatae praesentium laudantium minus repellendus qui, fugiat recusandae?"
    />
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: {
    Service
  }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
