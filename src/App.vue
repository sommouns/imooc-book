<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>

export default {
  mounted () {
    this.$store.dispatch('setFileName', '11')
  }
}

document.addEventListener('DOMContentLoaded', function () {
  const html = document.querySelector('html')
  let fontSize = window.innerWidth / 10
  fontSize = fontSize > 50 ? 50 : fontSize
  html.style.fontSize = fontSize + 'px'
  console.log(html.style.fontSize)
})
</script>

<style lang="scss">
  #app{
    height: 100%;
    width: 100%;
    overflow: hidden;
  }
</style>
