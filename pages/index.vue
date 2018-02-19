<template>
  <div class="index">
    <yz-header></yz-header>
    <div class="banner">banner</div>
    <div class="media-show">media-show-left</div>
    <div class="media-show">media-show-left</div>
    <div class="solutions">solutions</div>
    <div class="use">use</div>
    <div class="guarantee">guarantee</div>
    <div class="service">service</div>
    <div class="register">register</div>
    <div class="footer">footer</div>
  </div>
</template>

<script>
import '~/assets/scss/index.scss';

import YzHeader from '~/components/index/header.vue';

export default {
  components: {
    YzHeader
  }
}
</script>

<style>

</style>
