---
layout: post
title:  "20150813 - How Many Ways to Put Coins Into Cups"
date:   2015-08-13 18:52:55
categories: NumberTheory
author: ev3commander
---
Areteem每日一题2015年8月13日

<problem>
把十枚硬币装进三个杯子，要求每个杯子中的硬币数是奇数。第一问：给出一种符合条件的装法。第二问：共有多少种符合条件的装法？
Put ten coins into three cups, so that each cup contains an odd number of coins. First question: find one way to do this. Second question: how many different ways are there to do this?

</problem>


### Solution <button>Show / Hide</button>

<solution>
You will need to stack the cups together. Here is one example: 
<br/><br/>
<svg width="200">
  <line x1="5" y1="5" x2="10" y2="95" style="stroke:black" />
  <line x1="95" y1="5" x2="90" y2="95" style="stroke:black" />
  <line x1="90" y1="95" x2="10" y2="95" style="stroke:black" />
  <line x1="8" y1="65" x2="92" y2="65" style="stroke:black" />
  <line x1="105" y1="5" x2="110" y2="95" style="stroke:black" />
  <line x1="195" y1="5" x2="190" y2="95" style="stroke:black" />
  <line x1="190" y1="95" x2="110" y2="95" style="stroke:black" />
  <text x="42" y="50" style="font-size:35px">5</text>
  <text x="42" y="92" style="font-size:35px">2</text>
  <text x="142" y="80" style="font-size:35px">3</text>
</svg>
<br/>
In total, there are 15 ways to do it:
<br/>
((1))(9), ((1)2)(7), ((1)4)(5), ((1)6)(3),((1)8)(1)
<br/>
((3))(7), ((3)2)(5), ((3)4)(3), ((3)6)(1)
<br/>
((5))(5), ((5)2)(3), ((5)4)(1)
<br/>
((7))(3), ((7)2)(1)
<br/>
((9))(1)

</solution>

