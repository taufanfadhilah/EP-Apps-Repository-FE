<template>
  <div class="card">
    <div class="row">
      <div class="col-md-8">
        <p class="list-title">APK for AA-209</p>
        <p class="content">
          Hi tester, here i attach my APK for testing ticket number AA-209 and
          AA-211.
        </p>
      </div>
      <div class="col-md-4 text-right">
        <p class="date d-none d-lg-block">Monday, 2 November 2020</p>
        <div class="row float-right">
          <button class="btn btn-primary mr-3">Detail</button>
          <button class="btn btn-secondary">Download</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.card {
  background: #d4ebd0;
  box-shadow: 1px 1px 2px 2px rgba(51, 51, 51, 0.12);
  border-radius: 20px;
  border: 0px;
  min-height: 73px;
  padding: 8px 24px;
  margin-bottom: 16px;
}
.list-title {
  font-weight: 600;
  font-size: 14px;
  line-height: 21px;
  color: #333333;
  margin-bottom: 0px;
}
.content {
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 18px;
  color: #333333;
}
.date {
  font-style: italic;
  font-weight: normal;
  font-size: 12px;
  line-height: 18px;
  color: #7a7777;
}
.btn {
  width: 132px;
  border-radius: 10px;
  filter: drop-shadow(0px 1px 4px rgba(0, 0, 0, 0.25));

  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  color: #ffffff;

  &.btn-primary {
    background: #1a7cd2;
    border: 0px;
  }
  &.btn-secondary {
    background: #fc512f;
    border: 0px;
  }
}
</style>
