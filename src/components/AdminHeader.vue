<template>
  <!-- header -->
  <div class="header">
    <div class="inner">
      <h1><img alt="최상위권 수준별 맞춤 단과 러셀" src="../assets/images/main/logo.gif" /></h1>
      <div class="user-info">
        <strong>박선영(본사 관리자)님,</strong> 2023.6.28 14:17 로그인 하셨습니다.
        <a href="/russel/admin/logout.asp"><img src="../assets/images/btn_login.gif" alt="" /></a>
      </div>
    </div>
  </div>
  <!-- //header -->
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  height: 80px;
  padding:15px 10px;
  border-bottom:1px solid #ccc;
  box-sizing: border-box;
}
.header .inner {
  display: flex;
  justify-content:space-between;
  align-items: center;
  width:1206px;
}
.header .inner .user-info strong {font-size: 13px;font-weight: bold;color:#ff5117;vertical-align: middle;}
.header .inner .user-info a {vertical-align: middle;}
.header .inner .user-info {font-size: 13px;}
</style>
