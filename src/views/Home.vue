<template>


      <!-- store -->
  <section id="store" class="store py-5">
    <div class="container">
      <!-- section title -->
      <div class="row">
        <div class="col-10 mx-auto col-sm-6 text-center">
          <h1 class="text-capitalize">our <strong class="banner-title ">store</strong></h1>
        </div>
      </div>
      <!-- end of section title -->
      <!--filter buttons -->
      <div class="row">
        <div class=" col-lg-8 mx-auto d-flex justify-content-around my-2 sortBtn flex-wrap">
          <a href="#" class="btn btn-outline-secondary btn-black text-uppercase filter-btn m-2" data-filter="all"> all</a>
          <a href="#" class="btn btn-outline-secondary btn-black text-uppercase filter-btn m-2" data-filter="weapons">weapons</a>
          <a href="#" class="btn btn-outline-secondary btn-black text-uppercase filter-btn m-2" data-filter="upgrades">upgrades</a>
          <a href="#" class="btn btn-outline-secondary btn-black text-uppercase filter-btn m-2" data-filter="skinz">skinz</a>
          <a href="#" class="btn btn-outline-secondary btn-black text-uppercase filter-btn m-2" data-filter="loot-boxes">loot boxes</a>
        </div>
      </div>
      <!-- search box -->
      <div class="row">

        <div class="col-10 mx-auto col-md-6">
          <form>
            <div class="input-group mb-3">
              <div class="input-group-prepend ">
                <span class="input-group-text search-box" id="search-icon"><i class="fas fa-search"></i></span>
              </div>
              <input type="text" class="form-control" placeholder='item....' id="search-item">
            </div>

          </form>
        </div>
      </div>
      <!--end of filter buttons -->
      <!-- store  items-->
      <div class="row store-items" id="store-items">
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item skinz" data-item="skinz">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/skin-1.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">skin item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">5</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item upgrades" data-item="upgrades">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/upgrade-1.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">upgrade item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">5</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item weapons" data-item="weapons">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/weapon-1.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">weapon item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">5</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item loot-boxes" data-item="loot-boxes">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/loot-box1.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">loot box</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">5</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item skinz" data-item="skinz">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/skin-2.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">skin item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">10</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item upgrades" data-item="upgrades">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/upgrade-2.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">upgrade item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">10</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item weapons" data-item="weapons">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/weapon-2.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">weapon item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">10</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item loot-boxes" data-item="loot-boxes">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/loot-box2.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">loot box</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">10</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item skinz" data-item="skinz">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/skin-3.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">skin item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">15</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item upgrades" data-item="upgrades">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/upgrade-3.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">upgrade item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">15</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item weapons" data-item="weapons">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/weapon-3.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">weapon item</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">15</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->
        <!-- single item -->
        <div class="col-10 col-sm-6 col-lg-4 mx-auto my-3 store-item loot-boxes" data-item="loot-boxes">
          <div class="card ">
            <div class="img-container">
              <img src="../assets/img/loot-box3.jpg" class="card-img-top store-img" alt="">
              <span class="store-item-icon">
                <i class="fas fa-shopping-cart"></i>
              </span>
            </div>
            <div class="card-body">
              <div class="card-text d-flex justify-content-between text-capitalize">
                <h5 id="store-item-name">loot box</h5>
                <h5 class="store-item-value">£ <strong id="store-item-price" class="font-weight-bold">15</strong></h5>

              </div>
            </div>


          </div>
          <!-- end of card-->
        </div>
        <!--end of single store item-->

      </div>
    </div>
  </section>
  <!--end of store items -->

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import axios from 'axios'

export default {
  name: 'home',
  components: {
    HelloWorld
  },

  mounted () {
    axios.get('http://localhost:8000')
      .then(console.log)
  }
}
</script>
