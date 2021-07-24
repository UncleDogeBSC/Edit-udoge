<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        nuxtjs
      </h1>
      <h2 class="subtitle">
        $egoD Presale July 25th 8pm UTC
      </h2>
      <div class="links">
        <a
          href="https://dogereversed.com/"
          target="_blank"
          rel="noopener"
          class="button--green"
        >
          Join Presale
        </a>
        <a
          href="https://t.me/egodofficial"
          target="_blank"
          rel="noopener"
          class="button--grey"
        >
          Telegram
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
