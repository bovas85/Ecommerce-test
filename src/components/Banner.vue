<template>
    <div class="banner" ><b-jumbotron :style="{ backgroundImage: `url('${bannerImg}')` }" class="jumbotron">
      <div class="header">
        <h1>ECOMMERCE EXAMPLE</h1>
        <b-button variant="primary" href="#">Go to product</b-button>
      </div>
  </b-jumbotron></div>
</template>
<script>
export default {
   data() {
    return {
      bannerImg : require("../../src/assets/static/images/mainBcg.jpeg")
    }
  }
}
</script>
<style lang="scss" scoped>
.jumbotron {
  height: 700px;
    background-size: cover;
    border-radius: 0 !important;
    margin-bottom: 0;

    .header {
      float: right;
    margin-top: 20%;
    display: flex;
    flex-direction: column;
    h1 {
      color: white;
      font-size: 60px;
    }
    }
    .btn {
      width: 50%;
    }



}
</style>
