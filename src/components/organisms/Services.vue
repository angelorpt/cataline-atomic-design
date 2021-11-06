<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quidem animi, dolore laboriosam, soluta ea facere voluptates error dolores inventore quae fugit! Officiis non dolor velit inventore quia ea veniam?"
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quidem animi, dolore laboriosam, soluta ea facere voluptates error dolores inventore quae fugit! Officiis non dolor velit inventore quia ea veniam?"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Hic quidem animi, dolore laboriosam, soluta ea facere voluptates error dolores inventore quae fugit! Officiis non dolor velit inventore quia ea veniam?"
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
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
