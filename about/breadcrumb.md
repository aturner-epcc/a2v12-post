---
layout: section
title: Breadcrumb test
summary: see what happens
---




<p>#demo-carousel.carousel.slide(data-ride=&quot;carousel&quot;)<br>
ol.carousel-indicators<br>
- var i = 0;<br>
while i++ &lt; 3<br>
if i == 1<br>
li.active(data-target=&quot;#demo-carousel&quot;, data-slide-to='' + i)<br>
else<br>
li(data-target=&quot;#demo-carousel&quot;, data-slide-to='' + i)<br>
.carousel-inner(role=&quot;listbox&quot;)<br>
- var i = 0;<br>
while i++ &lt; 3<br>
if i == 1<br>
.carousel-item.active(<br>
data-src='../img/05_Entry_800.jpg<br>
)<br>
.carousel-caption<br>
h3= 'Test caption ' + i<br>
p= 'Test caption description ' + i<br>
else<br>
.carousel-item(data-src='../img/10_Entry_800.jpg)<br>
.carousel-caption<br>
h3= 'Test caption ' + i<br>
p= 'Test caption description ' + i<br>
a.left.carousel-control(<br>
href=&quot;#demo-carousel&quot;,<br>
role=&quot;button&quot;,<br>
data-slide=&quot;prev&quot;<br>
)<br>
span.icon-prev(aria-hidden=&quot;true&quot;)<br>
span.sr-only Previous<br>
a.right.carousel-control(<br>
href=&quot;#demo-carousel&quot;,<br>
role=&quot;button&quot;,<br>
data-slide=&quot;next&quot;<br>
)<br>
span.icon-next(aria-hidden=&quot;true&quot;)<br>
span.sr-only Next</p>



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