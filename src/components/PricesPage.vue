<template>
  <div class="PricesPageContainer">
    <h1 class="PricesPageTitle">Prices</h1>

    <section class="container-md">
      <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">

      <div class="col">
        <div class="card mb-4 rounded-3 shadow-sm">
          <div class="card-header py-3">
            <h4 class="my-0 fw-normal">Trial</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">€0<small class="text-muted fw-light">/mo</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>A free trial version of our service with limitations</li>
            </ul>
            <button type="button" class="w-100 btn btn-lg btn-outline-primary">Sign up for free</button>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card mb-4 rounded-3 shadow-sm">
          <div class="card-header py-3">
            <h4 class="my-0 fw-normal">Student</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">€5<small class="text-muted fw-light">/mo</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>Watch unlimited videos</li>
            </ul>
            <button type="button" class="w-100 btn btn-lg btn-primary">Get started</button>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="card mb-4 rounded-3 shadow-sm border-primary">
          <div class="card-header py-3 text-white bg-primary border-primary">
            <h4 class="my-0 fw-normal">Enterprise</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">€<small class="text-muted fw-light">/data storage</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>Upload videos</li>
            </ul>
            <button type="button" class="w-100 btn btn-lg btn-primary">Contact us</button>
          </div>
        </div>
      </div>
    </div>
    </section>
    
  </div>
</template>

<script>
export default {
  name: "PricesPage",
  props: {},
};
</script>


<style scoped>
.PricesPageContainer {
  background-color: #08379B;
  width: 100%;
  height: 90.5vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.PricesPageTitle {
    color: #c2c2c2;
    margin: 6rem;
}
</style>