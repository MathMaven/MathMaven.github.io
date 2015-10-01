---
layout: post
title:  "20150810 - Wooden Block Calendar"
date:   2015-08-10 18:52:55
categories: NumberTheory
---
<style>.cube-container {
  width: 200px;
  height: 200px;
  position: relative;
  perspective: 1000px;
  margin: 100px auto;
}
#cube {
  width: 100%;
  height: 100%;
  position: absolute;
  transform-style: preserve-3d;
  transform: translateZ( -100px ) rotateZ(45deg) rotateX(45deg);
  animation: spin 5s infinite linear;
}
@keyframes spin {
  0% { transform: translateZ( -100px ) rotateY(360deg) rotateZ(0deg) rotateX(45deg) }
  50% { transform: translateZ( -100px ) rotateY(180deg) rotateZ(180deg) rotateX(45deg) }
  100% { transform: translateZ( -100px ) rotateY(0deg) rotateZ(360deg) rotateX(45deg) }
}
#cube figure {
  width: 100%;
  height: 100%;
  display: block;
  position: absolute;
  line-height: 200px;
  background: rgba(56, 125, 25, 0.25);
font-size: 120px;
font-weight: bold;
color: #fff;
text-align: center;
  border: 1px dotted blue;
  backface-visibility: hidden;
}
#cube .front  { transform: rotateY(   0deg ) translateZ( 100px ); }
#cube .back   { transform: rotateX( 180deg ) translateZ( 100px ); }
#cube .right  { transform: rotateY(  90deg ) translateZ( 100px ); }
#cube .left   { transform: rotateY( -90deg ) translateZ( 100px ); }
#cube .top    { transform: rotateX(  90deg ) translateZ( 100px ); }
#cube .bottom { transform: rotateX( -90deg ) translateZ( 100px ); }</style>
You are required to design a desk calendar using wooden blocks. Given two wooden cubes as shown, write one digit on each of their faces, so that every date in a month, 01,02,03,......,30,31, can be displayed. Note that dates less than 10 have to be displayed with a leading 0.
<table>
  <tr>
    <th>
<div class="cube-container">
<div id="cube">
  <figure class="face front">6</figure>
  <figure class="face back">2</figure>
  <figure class="face left">3</figure>
  <figure class="face right">4</figure>
  <figure class="face top">5</figure>
  <figure class="face bottom">1</figure>
</div>
      </div></th>
   <th>    
<div class="cube-container">
<div id="cube">
  <figure class="face front">0</figure>
  <figure class="face back">1</figure>
  <figure class="face left">2</figure>
  <figure class="face right">7</figure>
  <figure class="face top">8</figure>
  <figure class="face bottom">9</figure>
</div>
  </div></th>
  </tr>
</table>

### Solution <button>Show/Hide</button>
<solution>
0, 1, 2, 3, 4, 5 on one cube and 0, 1, 2, 7, 8, 9 on the other. 9 is used as 6 when necessary.
</solution>

