<template>
  <div>
    <header class="header">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-md-3 col-12">
            <div class="logo">
              <nuxt-link to='/'>
                <img src='~/assets/images/logo.png'>
                <b>Nissin BlockChain training</b>
              </nuxt-link>
            </div>
            <div class="mobile-menu"></div>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style lang='scss'>
.logo {
  img {
    width: 100px;
  }
}
</style>
