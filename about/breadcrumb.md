---
layout: section
title: Breadcrumb test
summary: see what happens
---




<div class="carousel slide" id="demo-carousel" data-ride="carousel">
  <ol class="carousel-indicators">
    <li class="active" data-target="#demo-carousel" data-slide-to="1"></li>
    <li data-target="#demo-carousel" data-slide-to="2"></li>
    <li data-target="#demo-carousel" data-slide-to="3"></li>
  </ol>
  <div class="carousel-inner" role="listbox">
    <div class="carousel-item active" data-src="https://unsplash.it/800/400?random=1">
      <div class="carousel-caption">
        <h3>Test caption 1</h3>
        <p>Test caption description 1</p>
      </div>
    </div>
    <div class="carousel-item" data-src="https://unsplash.it/800/400?random=2">
      <div class="carousel-caption">
        <h3>Test caption 2</h3>
        <p>Test caption description 2</p>
      </div>
    </div>
    <div class="carousel-item" data-src="https://unsplash.it/800/400?random=3">
      <div class="carousel-caption">
        <h3>Test caption 3</h3>
        <p>Test caption description 3</p>
      </div>
    </div>
  </div><a class="left carousel-control" href="#demo-carousel" role="button" data-slide="prev"><span class="icon-prev" aria-hidden="true"></span><span class="sr-only">Previous</span></a><a class="right carousel-control" href="#demo-carousel" role="button" data-slide="next"><span class="icon-next" aria-hidden="true"></span><span class="sr-only">Next</span></a>
</div>


# end of first test




<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="../img/10_Entry_800.jpg" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../img/12_Entry_800.jpg" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../img/05_Entry_800.jpg" alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

# try it here

$('.carousel').carousel()

shoud be done