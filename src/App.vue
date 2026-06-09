<template>
  <div>
    <div class="header-bg" />

    <main class="main-content">
      <div class="login-container">
        <div class="title">登入 Threads</div>
        <LoginForm />
        <a href="#" class="forgot-link">忘記密碼？</a>
      </div>
    </main>

    <QrPanel />
    <FooterBar />
  </div>
</template>

<script>
import LoginForm from './components/LoginForm.vue'
import QrPanel from './components/QrPanel.vue'
import FooterBar from './components/FooterBar.vue'

export default {
  name: 'App',
  components: { LoginForm, QrPanel, FooterBar }
}
</script>

<style>
.header-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: url('/gf40BP6SRYU.avif');
  background-size: 100% auto;
  background-position: center top;
  background-repeat: no-repeat;
  z-index: 0;
  pointer-events: none;
}
</style>
