<template>
  <div class="card mb-8">
    <div class="row">
      <div class="col-md-12">
        <p class="submit-title">Submit Your Apps</p>
      </div>
      <div class="col-md-12 mt-24 mb-16">
        <label for="title mb-8">Title</label>
        <input type="text" class="form-control" placeholder="Enter title" />
      </div>
      <div class="col-md-12 mb-16">
        <label for="uploader mb-8">Uploader</label>
        <input type="text" class="form-control" placeholder="Enter title" />
      </div>
      <div class="col-md-12 mb-16">
        <label for="team mb-8">Team</label>
        <select name="" id="" class="form-control"></select>
      </div>
      <div class="col-md-12 mb-16">
        <label for="platform mb-8">Platform</label>
        <select name="" id="" class="form-control"></select>
      </div>
      <div class="col-md-12 mb-16">
        <label for="description mb-8">Description</label>
        <input type="text" class="form-control" placeholder="Enter title" />
      </div>
      <div class="col-md-12">
        <label for="link-for-download mb-8">Link for Download</label>
        <input type="url" class="form-control" placeholder="Enter title" />
      </div>
      <div class="col-md-12">
        <button class="btn btn-primary">Submit</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.card {
  padding: 24px;
  background: #ffffff;
  box-shadow: 0px 2px 4px 2px rgba(0, 0, 0, 0.15);
  border-radius: 20px 0px 0px 20px;
  border: 0px;
}
.submit-title {
  font-weight: 600;
  font-size: 18px;
  color: #333333;
  border-bottom: 3px solid #1a7cd2;
  padding-bottom: 8px;
}
.btn {
  margin-top: 32px;
  width: 100%;
  height: 50px;
  border-radius: 10px;
  filter: drop-shadow(0px 1px 4px rgba(0, 0, 0, 0.25));

  font-weight: 600;
  font-size: 18px;
  line-height: 30px;
  color: #ffffff;

  &.btn-primary {
    background: #1a7cd2;
    border: 0px;
  }
}
</style>
