---
layout: post
title:  "20150929 - Find the length of square"
date:   2015-09-29 15:30:55
categories: Geometry 
---
Areteem魔法学园每日一题2015年9月29日<br>
在正方形ABCD中，E、F、G分别是BC、AE、DF的中点。已知三角形BDG的面积为1，求AB的长度。<br>
In square ABCD, points E, F, and G are the midpoints of BC, AE, and DF respectively. Given that the area of triangle BDG is 1, find the length of AB.

<svg width="600" height="600">
    <g transform="translate(100, 100)">
      <rect x="0" y="0" width="400" height="400" stroke="black" stroke-width="4" fill="none" />
      <polygon points="0,0 100, 150 400, 400" fill="cyan" />
      <line x1="0" y1="0" x2="400" y2="400" stroke="black" stroke-width="2" />
      <line x1="0" y1="400" x2="400" y2="200" stroke="black" stroke-width="2" />
      <line x1="0" y1="0" x2="200" y2="300" stroke="black" stroke-width="2" />
      <line x1="100" y1="150" x2="400" y2="400" stroke="black" stroke-width="2" />
      <text x="-30" y="-10" font-size="24">D</text>
      <text x="-30" y="420" font-size="24">A</text>
      <text x="410" y="420" font-size="24">B</text>
      <text x="410" y="-10" font-size="24">C</text>
      <text x="410" y="210" font-size="24">E</text>
      <text x="200" y="320" font-size="24">F</text>
      <text x="80" y="170" font-size="24">G</text>
    </g>
  </svg>


### Solution <button>Show / Hide</button>

<solution>
         AH=HD , so area:   $\triangle$AHB = $\triangle$HDB <BR>
         HF=FB , so area:   $\triangle$HDF = $\triangle$DFB <BR>
         DG=GF , so area:   $\triangle$DGB = $\triangle$GFB <BR>
        So, area: $\triangle$ADB = 8 * $\triangle$DBG = 8 <BR>    

         AB=4
<br><br>
<svg width="600" height="600">
    <g transform="translate(100, 100)">
      <rect x="0" y="0" width="400" height="400" stroke="black" stroke-width="4" fill="none" />
      <polygon points="0,0 100, 150 400, 400" fill="cyan" />
      <line x1="0" y1="0" x2="400" y2="400" stroke="black" stroke-width="2" />
      <line x1="0" y1="400" x2="400" y2="200" stroke="black" stroke-width="2" />
      <line x1="0" y1="0" x2="200" y2="300" stroke="black" stroke-width="2" />
      <line x1="100" y1="150" x2="400" y2="400" stroke="black" stroke-width="2" />
      <line x1="0" y1="200" x2="400" y2="400" stroke="red" stroke-width="2" stroke-dasharray="10, 6"  />

      <text x="-30" y="-10" font-size="24">D</text>
      <text x="-30" y="420" font-size="24">A</text>
      <text x="410" y="420" font-size="24">B</text>
      <text x="410" y="-10" font-size="24">C</text>
      <text x="410" y="210" font-size="24">E</text>
      <text x="190" y="330" font-size="24">F</text>
      <text x="80" y="170" font-size="24">G</text>
      <text x="-30" y="210" font-size="24">H</text>

    </g>
  </svg>
</solution>
