<template>

  <div class="dc-jumbotron">
    <div class="row h-100 w-100 justify-content-center align-items-center">
      <div class="col-6">
        <h1 class="dc-jumbotron__search-title">Find 100M+ Products Online</h1>
        <div class="input-group mb-3">
          <div class="input-group-prepend">

            <div class="dropdown bg-light border-0 jumbotron-filter-bar">
              <button class="text-info btn btn-default border-0 dropdown-toggle" type="button" id="dropdownMenuButton1"
                data-bs-toggle="dropdown" aria-expanded="false">
                All
              </button>
              <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                <li>
                  <h6 class="dropdown-header">Find All</h6>
                </li>

                <li><a class="dropdown-item text-info" href="#">All</a></li>
                <li>
                  <h6 class="dropdown-header">Popular Store</h6>
                </li>
                <li><a class="dropdown-item text-info" href="#">Fastest Delivery</a></li>
                <li><a class="dropdown-item text-info" href="#">Warehouse Deals</a></li>
              </ul>
            </div>
          </div>
          <input type="text" class="border-0 form-control dc-search-container-search-bar"
            placeholder="Search for any product...">
        </div>
      </div>
    </div>
    <div class="row w-100 justify-content-center align-items-center">
          <div class="col-4">
            <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel" >
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">

      <div class="carousel-caption d-none d-md-block">

        <p class="text-white ">Over 100 Million Items.</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="2000">

      <div class="carousel-caption d-none d-md-block">

        <p class="text-white ">Secure and Convenient Shopping</p>
      </div>
    </div>
    <div class="carousel-item">

      <div class="carousel-caption d-none d-md-block">

        <p class="text-white ">3 Day Shipping Available</p>
      </div>
    </div>
  </div>

</div>
          </div>
        </div>
  </div>
</template>
