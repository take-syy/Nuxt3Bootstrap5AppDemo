<template>
  <div>
    <Navbar />
    <Nuxt />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'

export default {
  components: {
    Navbar
  }
}
</script>

<style scoped>
/* タイトルのスタイル */
h1 {
  font-size: 24px;
  color: #333;
  margin-bottom: 20px;
}

/* 画像のスタイル */
img {
  max-width: 100%;
  height: auto;
  margin-bottom: 20px;
}

/* テキストのスタイル */
p {
  font-size: 16px;
  color: #666;
  line-height: 1.5;
}
</style>