<template>
  <div>
    <div class="left-padding">
        <img src="../assets/shareimg/logo.png" alt="ろご" class="logo">
        <div class="flex icon-field">
          <img src="../assets/shareimg/home.png" alt="ホーム" class="icon">
          <p>ホーム</p>
        </div>
        <div
        class="flex icon-field">
          <img src="../assets/shareimg/profile.png" alt="" class="icon">
          <p>プロフィール</p>
        </div>
        <div class="flex icon-field">
          <img src="../assets/shareimg/logout.png" alt="" class="icon">
          <p>ログアウト</p>
        </div>
      </div>
      <hr />
      <ShareMessage />
  </div>
</template>

<script>
import ShareMessage from "../components/ShareMessage";
export default {
  components:{
    ShareMessage
  }
}
</script>

<style scoped>
.left-padding {
 margin: 20px;
}
.logo {
 width: 100px;
}
.icon-field {
 margin-top: 15px;
 cursor: pointer;
}
.icon-field p {
 font-size: 16px;
 padding-left: 15px;
}
.flex{
  display: flex;
}
.icon{
  width: 25px;
}
</style>