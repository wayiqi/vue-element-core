<template>
  <div class="page-view">
    <router-view />
    <div class="footer">
      <div class="copyright">
        Copyright &copy; zu1662
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'PageView'
}
</script>

<style lang='less' scoped>
  .page-view {
    padding: 2rem;
  }
</style>
