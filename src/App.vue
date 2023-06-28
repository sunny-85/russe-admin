<template>
  <AdminHeader />
  <LeftMenu />
  <div class="cont-wrapper">
  </div>
</template>

<script>
import AdminHeader from './components/AdminHeader'
import LeftMenu from './components/LeftMenu'
export default {
  name : "app",
  components: {
    AdminHeader,
    LeftMenu,
  }
}
</script>

<style>
  h1, body, div, p, span, li, u, * {padding:0;margin:0;}
  h1 {color:#03a9f4;}
  .cont-wrapper {margin:0 0 0 200px;}
</style>
