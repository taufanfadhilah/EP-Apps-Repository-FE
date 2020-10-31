<template>
  <div class="container-fluid">
    <VNavbar />
    <div class="row mt-16">
      <div class="col-md-9 col-sm-12">
        <VQuote />
        <div class="row">
          <div class="col-md-12">
            <p class="title mt-32">Apps Repository</p>
          </div>
          <div class="col-md-12">
            <VList />
            <VList />
            <VList />
          </div>
        </div>
      </div>
      <div class="col-md-3"><h1>hi</h1></div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.title {
  margin-top: 32px;
  font-weight: 600;
  font-size: 18px;
  line-height: 27px;
  color: #333333;
  border-bottom: 3px solid #1a7cd2;
  display: inline-block;
  padding-bottom: 2px;
}
</style>
