---
layout: post
title:  "20150817 - Find the Sum of Shades"
date:   2015-08-17 18:52:55
categories: Geometry
author: Wyzdm
---
Areteem每日一题2015年8月17日

Areteem Daily Magic Spells August 17

<problem>

如图所示，矩形ABCD的面积是48，E、F、G是各自边上的中点，求两个阴影部分面积之和。
<p>
As shown, the area of the rectangle ABCD is 48, and E, F, and G are the midpoints of the respective sides. Find the sum of the areas of the two shaded regions.
</p>
 <svg width="500" height="130">
  <rect width="300" height="100" style="fill:rgb(55,255,255);stroke-width:3;stroke:rgb(0,0,0)" />
        <line x1="200" y1="0" x2="0" y2="50" style="stroke:rgb(0,0,0);stroke-width:3" />
        <line x1="200" y1="0" x2="150" y2="100" style="stroke:rgb(0,0,0);stroke-width:3" />
       <text x="5" y="20" fill="black">A</text>
           <text x="5" y="45" fill="black">E</text>
           <text x="5" y="120" fill="black">D</text>
        <line 1 x1="200" y1="0" x2="300" y2="50" style="stroke:rgb(0,0,0);stroke-width:4" />
     <text x="150" y="120" fill="black">F</text>
     <text x="305" y="120" fill="black">C</text>
     <text x="305" y="60" fill="black">G</text>
    <text x="305" y="20" fill="black">B</text>
    <text x="200" y="20" fill="black">H</text>
<polyline points="200,1 2,50 2,99 150,99 200,1 299,2 299,50" fill="#FFA9A9" />
   <line x1="200" y1="0" x2="150" y2="100" style="stroke dasharray:rgb(0,0,0);stroke -width:3" />
</svg>


</problem>


### Solution <button>Show / Hide</button>

<solution>
<p> 
The way the question is stated and the picture in drawn, H can really be anywhere I want it to be. In this case, I want to make it so that H is the midpoint of AB. Also because the question is stated as it is, I can also decide the dimensions of the rectangle. In this case, I will make it so that $AB=8 and AD=6$. $EHFD=AHFD-AEH$. $AEH's$ area is $3*4/2=6$. AHFD=$4*6=24$. Therefore, EHFD has an area of $24-6=18$. $HGB=3*4/2=6$ so the answer is $18+6=24$
</p>
         <svg width="500" height="100">
  <rect width="300" height="100" style="fill:rgb(255,255,255);stroke-width:3;stroke:rgb(0,0,0)" />
        <line x1="200" y1="0" x2="0" y2="50" style="stroke:rgb(0,0,0);stroke-width:3" />
        <line x1="200" y1="0" x2="150" y2="100" style="stroke:rgb(0,0,0);stroke-width:3" />
       <text x="5" y="20" fill="black">A</text>
           <text x="5" y="45" fill="black">E</text>
           <text x="5" y="90" fill="black">D</text>
        <line 1 x1="200" y1="0" x2="300" y2="50" style="stroke:rgb(0,0,0);stroke-width:4" />
     <text x="140" y="92" fill="black">F</text>
     <text x="260" y="92" fill="black">C</text>
     <text x="305" y="60" fill="black">G</text>
    <text x="305" y="20" fill="black">B</text>
    <text x="200" y="30" fill="black">H</text>
    <g fill="none" stroke="black" stroke-width="4">
    <path stroke-dasharray="5,5" d="M5 96 l215 -105" />
          <path stroke-dasharray="5,5" d="M5 -170 1235 950" />
</svg>
           <h3>Solution 2</h3>
           <p>Drawing DH and HC, I get four triangle. Triangle HFC is equalin area to triangle HDF because the bases and the heights of the two triangles are the same. Triangle HDE has the same area as triangle HAE for the same reason. Triangle HGB is the same as triangle HGC. Everyone one of these case all include one part of the shaded reigon and one part of the non shaded reigon. Therefore, the non shaded reigon is equal in area to the shaded reigon. So the answer is the toal area divided by 2.$48/2=24$</p>
</solution>

