<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <h1>Welcome</h1>
        <div class="row logos">
          <img class="logo shoelace" src="https://shoelace.style/source/img/wordmark.svg" />
          <img class="logo vue" src="https://upload.wikimedia.org/wikipedia/commons/5/53/Vue.js_Logo.svg" />
        </div>

      </div>
      <div class="col">
        <p>🚧 Work in progress 🚧</p>
        <p>thank you for your patience 😊</p>
      </div>
    </div>
    <div class="row footer">
      <p>4uroraSkye &copy; {{ (new Date).getFullYear() }}</p>
    </div>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="scss" scoped>
  .logos {
    max-height: 80px;
    justify-content: center;
    .logo.shoelace {
      width: auto;
      max-width: 350px;
    }
    .logo.vue {
      width: auto;
      max-width: 80px;
      margin-left: -60px;
    }
  }
  .footer {
    position: absolute;
    bottom: 0;
    text-align: center;
    width: 100%;
    > * {
      width: 100%;
    }
  }
</style>
