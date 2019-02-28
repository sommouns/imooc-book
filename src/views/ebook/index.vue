<template>
  <div class="ebook">
    <EBookTitle />
    <EBookReader />
    <EBookMenuBar />
  </div>
</template>

<script>
import EBookReader from '../../components/ebook/EBookReader.vue'
import EBookTitle from '../../components/ebook/EBookTitle.vue'
import EBookMenuBar from '../../components/ebook/EBookMenu.vue'
export default {
  components: {
    EBookReader,
    EBookTitle,
    EBookMenuBar
  }
}
</script>

<style lang="scss" scoped>

</style>
