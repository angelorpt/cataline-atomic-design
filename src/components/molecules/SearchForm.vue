<template>
  <form class="search-form">
    <input type="search" placeholder="Buscar" />

    <button type="submit">
      <img src="@/assets/images/icons/search.svg" alt="Buscar" />
    </button>
  </form>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({})
</script>

<style lang="scss" scoped>
.search-form {
  position: relative;
  width: max-content;
  input {
    border: none;
    border-radius: 1rem;
    padding: 0.5rem 1rem;
    box-shadow: 0px 5px 5px rgba($color: #000000, $alpha: 0.08);
    &::placeholder {
      color: #a9b0be;
    }
  }
  button {
    position: absolute;
    right: 3px;
    top: 50%;
    transform: translateY(-50%);
    width: 30px;
    height: 30px;
    background: #ff895f;
    border: none;
    border-radius: 5rem;
    display: grid;
    justify-content: center;
    align-items: center;
  }
}
</style>
