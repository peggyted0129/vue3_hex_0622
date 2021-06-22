<template>
<section class="cart">
  <loading v-model:active="isLoading">
    <img src="https://upload.cc/i1/2021/06/12/N7mIQ1.gif
" alt="loading">
  </loading>
  <!-- banner -->
  <div class="w-100 cart-banner mb-12"></div>
  <div class="container mb-13">
    <div class="d-flex align-items-center justify-content-between mb-4">
      <h3 class="text-theme fw-bolder">購買清單</h3>
      <button class="btn btn-outline-danger" type="button">清空購物車</button>
    </div>
    <div class="row">
      <div class="col-12">
        <ul class="order py-4 px-0 px-sm-4">
          <li class="orderList">
            <div class="row flex-wrap">
              <div class="col-3 col-md-2">
                <div class="orderImg">
                  <img src="https://storage.googleapis.com/vue-course-api.appspot.com/ownspace%2F1582727558982.jpg?GoogleAccessId=firebase-adminsdk-zzty7%40vue-course-api.iam.gserviceaccount.com&Expires=1742169600&Signature=K9UbfozJU4m56PnEV6Rqu6RywJaj45mRw%2B3xfT9rrVX0Zy2eswnkcDen8TZOXCemi6CGwxUISvwm6UVY1PSLn6OeAAzcJRrQHb4rbZKG7z087s3pT9P%2FRxFfCA2KzEH55%2FxjvXq54mgAnYP27CBAg0UvmDzbAhb8Vx1zmLotcvlL0IQoSlCIYkdLu96fUI7mLeRAeJSeZC1YVeo%2B0j%2BRituIs0MI7fTTXlCFFGrZnKKXK%2Fm812e4otXKtV1qBAEi3D9V0kGoFBd2iQxXy4%2BvKEynfMqBIvs10BPqafLP2zBGmb2P6F5AOOPJWv47KvtBm6CcUWxggKEfmbjnau5okA%3D%3D" alt="">
                </div>
              </div>
              <div class="col-7 col-md-8">
                <div class="row mx-3 w-100">
                  <div class="col-12 col-md-5 pb-3 px-0">
                    <div class="orderTitle fw-bolder pt-md-9">產品名稱1234565</div>
                  </div>
                  <div class="col-12 col-md-4 pb-3 px-0 pt-md-9">
                    <div class="orderNum">
                      <div class="input-group justify-content-start align-items-center">
                        <button type="button" class="input-group-text">
                          <i class="fas fa-minus"></i>
                        </button>
                        <p class="form-control text-center m-0 cartNum py-2 px-2">10</p>
                        <button type="button" class="input-group-text">
                          <i class="fas fa-plus"></i>
                        </button>
                      </div>
                    </div>
                  </div>
                  <div class="col-12 col-md-3 p-0 pt-md-9 text-end">
                    <div class="orderTotal">小計 $420</div>
                  </div>
                </div>
              </div>
              <!-- <div class="col-2 p-0">
                <div class="orderTotal">總計 $420</div>
              </div> -->
              <div class="col-2 p-0 pt-md-9 text-end">
                <div class="orderDel px-3">
                  <i class="far fa-trash-alt"></i>
                </div>
              </div>
            </div>
          </li>
          <li class="orderList">
          </li>
        </ul>
      </div>
    </div>
  </div>
</section>
</template>
