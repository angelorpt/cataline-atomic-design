<template>
  <div class="social-networks">
    <SocialLink name="github" to="https://github.com" icon="github.svg" />
    <SocialLink name="twitter" to="https://twitter.com" icon="twitter.svg" />
    <SocialLink name="facebook" to="https://facebook.com" icon="facebook.svg" />
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  components: {
    SocialLink
  }
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
