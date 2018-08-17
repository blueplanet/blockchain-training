<template>
  <div>
    <header class="header">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-md-3 col-12">
            <div class="logo">
              <nuxt-link to='/'>
                <img src='~/assets/images/logo.png'>
                <b class='ml-1'>NBT</b>
              </nuxt-link>
            </div>
            <div class="mobile-menu"></div>
          </div>
          <div class="col-lg-9 col-md-9 col-12 d-flex align-items-center">
            <div class="header-widget">
              <div class="single-widget d-flex align-items-center">
                <span class="fa-stack fa-1x">
                  <i class="fa fa-phone text-primary fa-stack-1x"></i>
                  <i class="far fa-circle fa-stack-2x text-black-20"></i>
                </span>
                <div class='d-inline-block ml-1'>CallNow<span>031 111 2222</span></div>
              </div>
            </div>
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

.single-widget {

}

</style>
