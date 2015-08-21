# Gallerypractice
Gallery practice code
Takes images from a div and generates a gallery out of them.



<div class="Gallery">
  <img src="/img/sample1.jpg" />
  <img src="/img/sample2.jpg" />
  <img src="/img/sample3.jpg" />
  <img src="/img/sample4.jpg" />
</div>

would create something like this (with clickable thumbnails):

<div class="Gallery">
  <div id="jFull">
    <img src="/img/sample1.jpg">
  </div>
  <div id="jThumbs">
    <div style="margin-left: 0px; background-image: url(/img/sample2.jpg);" class="jThumb active"></div>
    <div style="background-image:url(/img/sample3.jpg);" class="jThumb"></div>
    <div style="background-image:url(/img/sample4.jpg);" class="jThumb"></div>
    <div style="margin-right: 0px; background-image: url(/img/sample1.jpg);" class="jThumb"></div>
  </div>
  <img src="/img/sample1.jpg" class="hidden">
  <img src="/img/sample2.jpg" class="hidden">
  <img src="/img/sample3.jpg" class="hidden">
  <img src="/img/sample4.jpg" class="hidden">
</div>

