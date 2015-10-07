---
layout: post
title:  "20150916 - Find the total area of the shaded regions"
date:   2015-09-16 10:50:51
categories: Geometry
author: richardwsong
---

Areteem魔法学园每日一题2015年9月16日

三个圆的半径都是1，且每个圆都经过另两个圆的圆心，如图所示。求阴影部分的总面积。

The radii of the three circles in the figure are all 1, and each circle passes through the centers of the other two circles. Find the total area of the shaded regions.

<svg width="350" height="350">
  <circle cx="100" cy="200" r="100" fill="white" style="stroke:rgb(0,0,0);stroke-width:1;fill-opacity:0"/>
  <circle cx="200" cy="200" r="100" fill="white" style="stroke:rgb(0,0,0);stroke-width:1;fill-opacity:0"/>
  <circle cx="150" cy="114" r="100" fill="white" style="stroke:rgb(0,0,0);stroke-width:1;fill-opacity:0"/>  
  
<path d="M50 114
           A 100 100, 0, 0, 0, 100 200
           A 100 100, 0, 0, 1, 150 114
          A 100 100, 0, 0, 0, 50 113
           " fill="lightblue"/>
  
 <path d="M150 113
           A 100 100, 0, 0, 1, 250 114
           A 100 100, 0, 0, 1, 200 200
           A 100 100, 0, 0, 0, 150 114           
           " fill="lightblue"/>
  
  <path d="M200 200
           A 100 100, 0, 0, 1, 150 287
           A 100 100, 0, 0, 1, 100 200
           A 100 100, 0, 0, 0, 200 200
           " fill="lightblue"/>
</svg>

### Solution <button>Show / Hide</button>

<solution>
	We can make an imaginary line to create areas a and b and also a circle identical to the three other ones to make area c so that the area of a+b=c. Also, we notice that the area of e equals the area of d. Therefore, the area of the shaded regions equals a semi-circle with radius 1. The area of the semi-circle is $\frac{\pi}{2}$. Thus, the area of the 3 shaded regions is $\frac{\pi}{2}$.


<svg width="400" height="400">
  <circle cx="100" cy="200" r="100" fill="white" style="stroke:rgb(0,0,0);stroke-width:1;fill-opacity:0"/>
  <circle cx="200" cy="200" r="100" fill="white" style="stroke:rgb(0,0,0);stroke-width:1;fill-opacity:0"/>
  <circle cx="150" cy="114" r="100" fill="white" style="stroke:rgb(0,0,0);stroke-width:1;fill-opacity:0"/>  
  
   <circle cx="150" cy="287" r="100" fill="white" style="stroke:rgb(0,0,0);stroke-width:1;fill-opacity:0;stroke-dasharray: 10 5"/> 

  
  
<path d="M50 114
           A 100 100, 0, 0, 0, 100 200
           A 100 100, 0, 0, 1, 150 114
          A 100 100, 0, 0, 0, 50 113
           " fill="lightblue"/>
<path d="M150 113
           A 100 100, 0, 0, 1, 250 114
           A 100 100, 0, 0, 1, 200 200
           A 100 100, 0, 0, 0, 150 114           
           " fill="lightblue"/>
<path d="M200 200
           A 100 100, 0, 0, 1, 150 287
           A 100 100, 0, 0, 1, 100 200
           A 100 100, 0, 0, 0, 200 200
           " fill="lightblue"/>
 <line x1="50" y1="113" x2="250" y2="113" style="stroke:black;stroke-dasharray: 10 5"/>
 <text x="100" y="110">a</text>
 <text x="200" y="110">b</text>
 <text x="150" y="200">c</text>
 <text x="150" y="150">d</text>
 <text x="150" y="250">e</text> 
</svg>
</solution>
