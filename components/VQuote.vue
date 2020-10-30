<template>
  <div class="card">
    <div class="row">
      <div class="col-md-9 col-12">
        <p class="title mb-8">Quote of the Day</p>
        <p class="quote mb-0">
          Life is really simple, but men insist on making it complicated.
        </p>
        <p class="quote">~ Confucius</p>
      </div>
      <div class="col-md-3 d-none d-lg-block">
        <img
          src="@/static/checklist.png"
          alt="checklist illustration"
          class="img-checklist"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.card {
  box-shadow: 0px 2px 4px 3px rgba(51, 51, 51, 0.05);
  border-radius: 20px;
  padding: 16px 24px;
  border: 0px;
  margin-top: 3rem;
}
.title {
  font-weight: 600;
  font-size: 16px;
  color: #333333;
}
.quote {
  font-size: 14px;
  color: #333333;
  font-style: italic;
  font-weight: normal;
  line-height: 21px;
}
.img-checklist {
  width: 180px;
  height: 137.58px;
  margin-top: -4rem;
}
</style>
