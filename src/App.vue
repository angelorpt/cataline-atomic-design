<template>
  <div class="component">
    <Container>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore iusto
        totam iste aperiam a distinctio exercitationem amet soluta sint ipsam!
        Fugiat magni suscipit ducimus cupiditate numquam iste hic, quae
        explicabo?
      </p>
    </Container>
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import { Container } from '@/components/bosons'

export default defineComponent({
  components: {
    Container
  }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
