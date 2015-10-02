---
layout: post
title:  "20150728 - Find Degree of Angle in a Square"
date:   2015-07-28 18:52:55
categories: Geometry Trigonometry
---

In square ABCD, let E and F be points on BC and CD respectively, and BE=1, EF=4, FD=3. Find the measure of $\angle$EAF in degrees.

<svg width="250" height="250">
  <rect x="15" y="15" width="200" height="200" style="fill:none;stroke:blue;stroke-width:1"/>

  <text x="4" y="15" fill="blue">A</text>
  <text x="214" y="15" fill="blue">B</text>
  <text x="214" y="222" fill="blue">C</text>
  <text x="4" y="222" fill="blue">D</text>

  <text x="214" y="70" fill="red">E</text>
  <text x="120" y="230" fill="red">F</text>
  <text x="215" y="45" fill="blue">1</text>
  <text x="80" y="230" fill="blue">3</text>
  <text x="170" y="165" fill="blue">4</text>


  <line x1="15" y1="15" x2="214" y2="60" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <line x1="214" y1="60" x2="116" y2="214" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <line x1="15" y1="15" x2="116" y2="214" style="stroke:rgb(255,0,0);stroke-width:1"/>
  
</svg>


### Solution <button>Show / Hide</button>

<solution>
Extend line segment CD to point G, let DG = 1. By construction $\triangle$ABE $\cong$ $\triangle$ADG, then line AG = AE, and EF = 4 = (GD + DF) = GF, so $\triangle$AGF $\cong$ $\triangle$AEF. <br>
Also $\angle$BAE = $\angle$DAG, and $\angle$BAD = 90&deg;, so $\angle$EAG = 90&deg;. <br>
Then we know $\angle$EAF = $\frac{1}{2}\angle$EAG = 45&deg;.
<br><br>
<svg width="350" height="250">
  <rect x="65" y="15" width="200" height="200" style="fill:none;stroke:blue;stroke-width:1"/>

  <text x="64" y="15" fill="blue">A</text>
  <text x="274" y="15" fill="blue">B</text>
  <text x="274" y="222" fill="blue">C</text>
  <text x="64" y="230" fill="blue">D</text>

  <text x="274" y="70" fill="red">E</text>
  <text x="170" y="230" fill="red">F</text>
  <text x="271" y="45" fill="blue">1</text>
  <text x="130" y="230" fill="blue">3</text>
  <text x="205" y="150" fill="blue">4</text>
  <text x="30" y="230" fill="green">1</text>

  <line x1="65" y1="15" x2="264" y2="60" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <line x1="264" y1="60" x2="176" y2="214" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <line x1="65" y1="15" x2="176" y2="214" style="stroke:rgb(255,0,0);stroke-width:1"/>

  <text x="1" y="230" fill="green">G</text>
  <line x1="10" y1="214" x2="70" y2="214" style="stroke:rgb(0,255,0);stroke-width:1"/>
  <line x1="10" y1="214" x2="65" y2="15" style="stroke:rgb(0,255,0);stroke-width:1"/>
  
</svg>
</solution>

