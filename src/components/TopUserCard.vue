<template>
  <div class="top-user-card">
    <img src="../components/icons/user-avatar.jpg" alt="用户头像" class="avatar" />
    <div class="user-info">
      <h2>吉田龍生</h2>
      <h5>連接設備：</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: 'UserProfile'
}
</script>

<style scoped>
.top-user-card {
  display: flex;
  align-items: center;
}
.avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-right: 15px;
}
</style>
