<template>
  <div class="container-fluid">
    <VNavbar />
    <div class="row mt-16">
      <div class="col-md-8 col-sm-12 pl-5">
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
      <div class="col-md-4">
        <VSubmitApp />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.title {
  font-weight: 600;
  font-size: 18px;
  line-height: 27px;
  color: #333333;
  border-bottom: 3px solid #1a7cd2;
  display: inline-block;
  padding-bottom: 2px;
}
</style>
