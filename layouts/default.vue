<template>
  <nav>
    <nuxt-link to="/">ホーム</nuxt-link>
    <nuxt-link to="/school">学校紹介</nuxt-link>
  </nav>
</template>

<style lang="scss" scoped>
.modal {
  position: fixed;
  top: 0;
  width: 100%;
  height: 100%;
  .modal-wrap {
    background-color: rgba(0,0,0,0.5);
    height: 100%;
  }
}
</style>

