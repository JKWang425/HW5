<template>
  <form @submit.prevent="handleSubmit" class="login-form">
    <div class="input-group">
      <input v-model="username" type="text" class="input-field" placeholder="用戶名稱、手機號碼或電子郵件地址" required />
    </div>
    <div class="input-group">
      <input v-model="password" type="password" class="input-field" placeholder="密碼" required />
    </div>
    <button type="submit" class="login-btn">登入</button>
  </form>
</template>

<script>
export default {
  name: 'LoginForm',
  data() {
    return { username: '', password: '' }
  },
  methods: {
    handleSubmit() {
      alert('你被騙了!')
    }
  }
}
</script>
