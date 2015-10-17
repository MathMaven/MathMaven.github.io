---
layout: post
title:  "20150914 - Reassemble the Pieces Into a Regular Hexagon"
date:   2015-09-14 11:52:55
categories: Geometry
author: richardwsong
---

Areteem魔法学园每日一题2015年9月14日
<br>
<problem>
<p>	
图中的菱形由两个正三角形组成。把图中的菱形剪成4块，重新拼接成一个正六边形。
</P>
<p>
The rhombus in the figure is made up of two equilateral triangles. Cut the rhombus into 4 pieces and reassemble the pieces into a regular hexagon.
</p>
<svg width="350px" height="300px" >
  <g transform="translate(44, 10) scale(0.9 0.9)">
   <line x1 = "100" y1 = "0" x2 = "243" y2 = "83" stroke = "black" stroke-width = "3"/>
   <line x1 = "100" y1 = "0" x2 = "-43" y2 = "83" stroke = "black" stroke-width = "3"/>
   <line x1 = "-43" y1 = "83" x2 = "100" y2 = "166" stroke = "black" stroke-width = "3"/>
   <line x1 = "243" y1 = "83" x2 = "100" y2 = "166" stroke = "black" stroke-width = "3"/>
</g>
    
 </svg>
</problem>



### Solution <button>Show / Hide</button>


<solution>
<svg width="350px" height="300px" >
  <g transform="translate(44, 10) scale(0.9 0.9)">
   <line x1 = "100" y1 = "100" x2 = "243" y2 = "183" stroke = "black" stroke-width = "3"/>
   <line x1 = "100" y1 = "100" x2 = "-43" y2 = "183" stroke = "black" stroke-width = "3"/>
   <line x1 = "-43" y1 = "183" x2 = "100" y2 = "266" stroke = "black" stroke-width = "3"/>
   <line x1 = "243" y1 = "183" x2 = "100" y2 = "266" stroke = "black" stroke-width = "3"/>
  
   <line x1 = "-43" y1 = "183" x2 = "243" y2 = "183" stroke = "black" stroke-width = "1" stroke-dasharray="5, 2" />  
  
  <polygon style="fill:none;stroke:blue;stroke-width:2px"
             points="148,183.138438763306 52,183.138438763306 4,100 52,16.8615612366939 148,16.8615612366939 196,99.9999999999999 148,183.138438763306" stroke-dasharray="10, 1"  />
  
	<line x1 = "4" y1 = "100" x2 = "196" y2 = "100" stroke = "black" stroke-width = "1" stroke-dasharray="10, 1" />
	<line x1 = "52" y1 = "183" x2 = "23" y2 = "220" stroke = "blue" stroke-width = "2"  stroke-dasharray="10, 1" />
	<line x1 = "148" y1 = "183" x2 = "183" y2 = "220" stroke = "blue" stroke-width = "2" stroke-dasharray="10, 1" />

	<line x1 = "100" y1 = "100" x2 = "28" y2 = "55" stroke = "blue" stroke-width = "2" stroke-dasharray="10, 1" />
	<line x1 = "100" y1 = "100" x2 = "170" y2 = "55" stroke = "blue" stroke-width = "2" stroke-dasharray="10, 1" />

	<text x="10" y="170" font-size="12">1</text>
	<text x="30" y="120" font-size="12">1</text>
	<text x="160" y="120" font-size="12">2</text>
	<text x="180" y="170" font-size="12">2</text> 
	<text x="100" y="150" font-size="12">3</text>
	<text x="100" y="230" font-size="12">4</text>
	<text x="100" y="60" font-size="12">4</text>
	<text x="-40" y="200" font-size="12">A</text>
	<text x="240" y="200" font-size="12">B</text>
	<text x="50" y="200" font-size="12">C</text> 
	<text x="150" y="200" font-size="12">D</text>  
    
      </g>
     <style type="text/css"><![CDATA[
      svg {
        margin-bottom:-50px;
        transform-origin: 0% 0%;

      }
    ]]></style>
</svg>

</solution>
