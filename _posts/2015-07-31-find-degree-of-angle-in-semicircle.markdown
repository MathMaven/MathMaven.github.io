---
layout: post
title:  "20150731- Find Degree of Angle in Semicircle"
date:   2015-07-31 18:52:55
categories: Geometry Circle
---

In the diagram below, AB is the diameter of the semicircle. $\angle$CAB is 45&deg;, E is the midpoint of AC, and DE // AB. Find $\angle$ACD in degrees. O is the center of the circle.

<svg width="250" height="250" style="stroke:blue;stroke-width:1">

  <path d="M50,100 A90,90 0 1,1 230,100" fill="none" />

  <line x1="50" y1="100" x2="230" y2="100" style="stroke:blue;stroke-width:1"/>
  <line x1="50" y1="100" x2="140" y2="10" style="stroke:red;stroke-width:1"/>
  <line x1="65" y1="50" x2="100" y2="50" style="stroke:red;stroke-width:1"/>
  <line x1="65" y1="50" x2="140" y2="10" style="stroke:red;stroke-width:1"/>

  <text x="35" y="110" fill="blue">A</text>
  <text x="240" y="110" fill="blue">B</text>
  <text x="140" y="12" fill="blue">C</text>
  <text x="50" y="50" fill="blue">D</text>
  <text x="120" y="50" fill="blue">E</text>
  <text x="135" y="115" fill="blue">O</text>
  <text x="120" y="28" fill="none" style="stroke:red; font-size: 12px;" >?</text>
</svg>


### Solution <button>Show / Hide</button>

<solution>
First, create two lines CO and DO. Then, CO = DO. Extend DE to a point on CO. Call it M. Since E is the midpoint of AC, $\triangle$CEM $\sim \triangle$CAO. Since CE:AC = 1:2, CM:MO = 1:2, and M is the midpoint of CO. Also, since DM // AB, DM is an altitude of $\triangle$CDO. Since $\angle$CAB = 45&deg;, $\angle$ACO = 45&deg;. Because DM is both an altitude and a median, DC = DO, so $\triangle$CDO is equilateral. Then, $\angle$DCO = 60&deg;, and $\angle$ACD = 60&deg; - 45&deg; = 15&deg;. <br><br>

<svg width="250" height="250" style="stroke:blue;stroke-width:1">

  <path d="M50,100 A90,90 0 1,1 230,100" fill="none" />

  <line x1="50" y1="100" x2="230" y2="100" style="stroke:blue;stroke-width:1"/>
  <line x1="50" y1="100" x2="140" y2="10" style="stroke:red;stroke-width:1"/>
  <line x1="65" y1="50" x2="100" y2="50" style="stroke:red;stroke-width:1"/>
  <line x1="65" y1="50" x2="140" y2="10" style="stroke:red;stroke-width:1"/>
  <line x1="140" y1="100" x2="140" y2="10" style="stroke:green;stroke-width:1"/>
  <line x1="140" y1="100" x2="65" y2="50" style="stroke:green;stroke-width:1"/>
  <line x1="140" y1="50" x2="100" y2="50" style="stroke:green;stroke-width:1"/>

  <text x="35" y="110" fill="blue">A</text>
  <text x="240" y="110" fill="blue">B</text>
  <text x="140" y="12" fill="blue">C</text>
  <text x="50" y="50" fill="blue">D</text>
  <text x="120" y="50" fill="blue">E</text>
  <text x="150" y="50" fill="blue">M</text>
  <text x="135" y="115" fill="blue">O</text>
</svg>

</solution>

