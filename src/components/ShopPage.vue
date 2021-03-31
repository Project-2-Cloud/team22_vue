<template>
  <div class="ShopPageContainer">
    <h1 class="ShopPageTitle">License Shop</h1>
    <section>
      <div class="container-md">
        <div class="row">
          <div class="col-sm">
            <div class="card" style="width: 18rem">
              <img class="card-img-top" src="https://via.placeholder.com/300" alt="Card image cap" />
              <div class="card-body">
                <h5 class="card-title">License Name</h5>
                <p class="card-text">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <a href="#" class="btn btn-primary">Buy License Key</a>
              </div>
            </div>
          </div>
          <div class="col-sm">
            <div class="card" style="width: 18rem">
              <img class="card-img-top" src="https://via.placeholder.com/300" alt="Card image cap" />
              <div class="card-body">
                <h5 class="card-title">License Name</h5>
                <p class="card-text">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <a href="#" class="btn btn-primary">Buy License Key</a>
              </div>
            </div>
          </div>
          <div class="col-sm">
            <div class="card" style="width: 18rem">
              <img class="card-img-top" src="https://via.placeholder.com/300" alt="Card image cap" />
              <div class="card-body">
                <h5 class="card-title">License Name</h5>
                <p class="card-text">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
                <a href="#" class="btn btn-primary">Buy License Key</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "ShopPage",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.ShopPageContainer {
  background-color: #08379B;
  width: 100%;
  height: 90.5vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.ShopPageTitle {
    color: #c2c2c2;
    margin: 6rem;
}
</style>
