---
layout: post
title:  "20150908 - Find the Area of the Octagon"
date:   2015-09-08 11:52:55
categories: Geometry
author: richardwsong Wyzdm ev3commander
---


Areteem魔法学园每日一题2015年9月8日
<br>
<problem>
<p>	
等角八边形的八条边中，四条边长为3，另四条边长为根号2，且两种边长交替排列。求八边形的面积。
</P>
<p>
An equiangular octagon has four sides of length 3, and four sides of length square root of 2. The two lengths alternate. Find the area of the octagon.
</p>
</problem>



### Solution <button>Show / Hide</button>


<solution>

	<center>
<svg width="500" height="500">
    <g transform="translate(44, 10) scale(0.4 0.4)">
  <rect width="500" height="500" style="fill:none;stroke:black;stroke-width:2px" stroke-dasharray="10, 3" />
  <line x1="400" y1="0" x2="500" y2="100" stroke = "blue" stroke-width = "4" />
  <line x1="100" y1="0" x2="0" y2="100" stroke = "blue" stroke-width = "4" />
  <line x1="0" y1="400" x2="100" y2="500" stroke = "blue" stroke-width = "4"  />
  <line x1="500" y1="400" x2="400" y2="500" stroke = "blue" stroke-width = "4"  />
  <line x1="100" y1="0" x2="400" y2="0" stroke = "blue" stroke-width = "4"  />
  <line x1="0" y1="100" x2="0" y2="400" stroke = "blue" stroke-width = "4"  />
  <line x1="100" y1="500" x2="400" y2="500" stroke = "blue" stroke-width = "4"  />
  <line x1="500" y1="400" x2="500" y2="100" stroke = "blue" stroke-width = "4" />
  </g>
 <style type="text/css"><![CDATA[
      svg {
        margin-bottom:-250px;
        transform-origin: 0% 0%;

      }
    ]]></style>
</svg>
</center>

We create a square of side length 5 around our octagon. The longer blue edges are 3 and the shorter blue edges are $\sqrt{2}$. The total area of the square is 25 and the total areas of the little triangles is 2. Therefore, the area of the octagon is 25-2 = <b>23</b>.

</solution>










