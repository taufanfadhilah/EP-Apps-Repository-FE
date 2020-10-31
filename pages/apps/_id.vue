<template>
  <div class="row mt-16">
    <div class="col-md-8 col-sm-12 pl-5">
      <div class="row">
        <div class="col-md-12">
          <p class="title mt-32">APK for AA-209</p>
        </div>
      </div>
      <div class="row mt-40 mb-16">
        <div class="col-md-4"><p>Created At:</p></div>
        <div class="col-md-8"><p>Monday, 2 November 2020 - 13:20</p></div>
      </div>
      <div class="row mb-16">
        <div class="col-md-4"><p>Uploaded By:</p></div>
        <div class="col-md-8"><p>Hafidh Rizqifaluthi</p></div>
      </div>
      <div class="row mb-16">
        <div class="col-md-4"><p>Team:</p></div>
        <div class="col-md-8"><p>Agent App</p></div>
      </div>
      <div class="row mb-16">
        <div class="col-md-4"><p>Platform:</p></div>
        <div class="col-md-8">
          <p><span class="badge">iOS</span></p>
        </div>
      </div>
      <div class="row mb-16">
        <div class="col-md-4"><p>Description:</p></div>
        <div class="col-md-8">
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nam quae
            cumque, recusandae est quas temporibus ipsum ipsa unde odio sit
            atque alias magni optio iste reprehenderit dignissimos ducimus
            neque! Quos.Sit alias animi nesciunt optio odio quam cupiditate
            atque dolorem vel adipisci? Magnam, eos illum rerum sapiente
            dignissimos iure sit veritatis numquam ab maxime, voluptates, totam
            cupiditate quae quas dicta.
          </p>
        </div>
      </div>
      <div class="row fixed-bottom">
        <button class="btn btn-secondary">Download</button>
      </div>
    </div>
    <div class="col-md-4">
      <VSubmitApp />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.title {
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 36px;
  color: #333333;
  border-bottom: 3px solid #1a7cd2;
  padding-bottom: 2px;
  display: inline-block;
}
p {
  margin-bottom: 0px;
  font-weight: 500;
  font-size: 18px;
  line-height: 27px;

  color: #333333;
}
.fixed-bottom {
  margin-bottom: 8px;
  margin-left: 2rem;
}
.btn-secondary {
  width: 220px;
  background: #fc512f;
  border-radius: 5px;

  font-weight: 600;
  font-size: 18px;
  line-height: 27px;
  /* identical to box height */

  color: #ffffff;
  border: 0px;
}
.badge {
  // background: #3ac808; // for andro
  background: #93bde1; // for ios
  border-radius: 10px;
  padding: 6px 10px;
  font-weight: 500;
  font-size: 12px;
  line-height: 18px;
  align-items: center;

  color: #ffffff;
}
</style>
