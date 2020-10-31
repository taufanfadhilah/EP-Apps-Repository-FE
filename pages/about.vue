<template>
  <div class="row pl-5">
    <div class="col-md-12">
      <p class="title mt-32">Tech Stack</p>
    </div>
    <div class="col-md-12">
      <div class="row">
        <img src="@/static/mongo-logo.png" alt="mongo logo" />
        <img src="@/static/express-logo.png" alt="express logo" />
        <img src="@/static/vue-logo.svg" alt="vue logo" />
        <img src="@/static/node-logo.png" alt="node logo" />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.title {
  font-weight: 600;
  font-size: 24px;
  line-height: 27px;
  color: #333333;
  border-bottom: 3px solid #1a7cd2;
  display: inline-block;
  padding-bottom: 2px;
}
img {
  height: 100px;
  margin-right: 16px;
}
</style>
