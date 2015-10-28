---
layout: post
title:  "20151027 - What is the Maximum Possible Sum?  *"
date:   2015-10-27 17:42:27
categories: NumberTheory
author: richardwsong Wyzdm ev3commander
---
Areteem魔法学园每日一题2015年10月27日
<br>

<problem>
<p>	
一堆石子共25个，任意分成两堆，把两堆石子的个数相乘，得到一个乘积。再把其中一堆分成两堆，这两小堆的石子个数相乘，又得到一个乘积。依此类推，只要某堆石子至少两个，就可以分成两堆，得到一个乘积，直到每堆都只有一个石子为止。把所有得到的乘积加起来，这个总和最大是多少？
</P>
<p>

Twenty-five stones are in a pile. Split the pile into two smaller piles, calculate the product of the numbers of stones in each pile. Then split one of the piles into two even smaller piles, and calculate the product of the numbers of stones in these new piles. Keep going, as long as one of the piles contains at least two stones, split it into two piles and calculate the product, until every pile has only one stone. Now add all the products obtained during the process. What is the maximum possible sum?
</p>

</problem>



### Solution <button>Show / Hide</button>


<solution>
这个问题等价于握手问题。把25个石子看成25个人，每次把一组分成两组，每个人都和另一组的每个人握手，本组的人不握手，两数的乘积相当于握手次数。最后所有分组完成后，每两个人都握过一次手，所有乘积之和就是握手的总次数。因此答案是C(25,2)=25*24/2=300，与分组方法无关。
</solution>
