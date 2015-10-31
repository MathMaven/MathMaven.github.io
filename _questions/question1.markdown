---
layout: question
title:  "What the Number of Distinct Paths of Exactly n Jumps Ending at E?"
date:   2015-10-30 17:42:27
categories: NumberTheory
source: 老杨 Q086
level: 中级IMO
author: richardwsong Wyzdm ev3commander
---

<problem>
<p>	
已知A和E为正八边形的一组相对顶点。一只青蛙从点A开始跳跃，如果青蛙在任一个异于E的顶点，那么它可以跳到两个相邻顶点之一，而当它跳到点E时就停在那里，求经过n步跳跃到达E点的不同路线的条数。
</P>
<p>
Let A and E be opposite vertices of a regular octagon. A frog starts jumping at vertex A. From any vertex of the octagon except E, it may jump to either of the two adjacent vertices. When it reaches vertex E, the frog stops and stays there. What the number of distinct paths of exactly n jumps ending at E.
</p>
</problem>

### Solution <button>Show / Hide</button>


<solution>
44576<br>
a(4)=2<br>
a(6)=8<br>
a(2n)=4a(2n-2)-2a(2n-2)<br>
a(8)=4*8-2*2=28<br>
a(10)=4*28-2*8=96<br>
a(12)=4*96-2*28=328<br>
a(14)=4*328-2*96=1120<br>
a(16)=4*1120-2*328=3824<br>
a(18)=4*3824-2*1120=13056<br>
a(20)=4*13056-2*3824=44576<br>

</solution>