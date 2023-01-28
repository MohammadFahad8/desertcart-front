<template>
  <div class="container">
  <div id="testimonial-slider" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#testimonial-slider" data-slide-to="0" class="active"></li>
      <li data-target="#testimonial-slider" data-slide-to="1"></li>
      <li data-target="#testimonial-slider" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <div class="testimonial-card">
          <p>Testimonial 1</p>
          <h4>Name 1</h4>
        </div>
      </div>
      <div class="carousel-item">
        <div class="testimonial-card">
          <p>Testimonial 2</p>
          <h4>Name 2</h4>
        </div>
      </div>
      <div class="carousel-item">
        <div class="testimonial-card">
          <p>Testimonial 3</p>
          <h4>Name 3</h4>
        </div>
      </div>
    </div>
    <a class="carousel-control-prev" href="#testimonial-slider" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#testimonial-slider" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

</template>
