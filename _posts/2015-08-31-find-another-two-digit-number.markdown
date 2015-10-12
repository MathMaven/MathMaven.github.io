---
layout: post
title: "20150831 - Find Another Two Digit Number "
date: 2015-08-31 18:52:55
categories: NumberTheory
author: richardwsong
---

Areteem每日一题2015年8月31日

Areteem Daily Magic Spells August 31

<problem>
以25结尾的数，平方以后仍然以25结尾。能否找出另一个两位数，凡是以这两位数结尾的数，平方以后最后两位还是这两位？

If a number ends with 25, its square also ends with 25. Can you find another two digit number, such that for any number ending with these two digits, the square also ends with the same two digits?
</problem>


### Solution <button>Show / Hide</button>

<solution>
First, we want to find the units digit of all of the numbers ,x, in which x's square ends with x. With simple computation, we figure that these numbers must end in 0,1,5,and 6 because all of those 4 numbers squared end in those numbers. (0^2=<b>0</b>, 1^2 = <b>1</b>, 5^2= 2<b>5</b>, 6^2 = 3<b>6</b>). Now that we have the possible units digits, we can start to test numbers that end with these units digits<br> to see if they work. We can test all the numbers that end in these units digits only once if we create a variable, n, which stands for the tens digit of the number. We can make 4 cases, n0^2, n1^2, n5^2, and  n6^2. <br>


<b>Case 1</b>: When we square n0, the total tens digit equals n * 0 + n * 0 = 2n + 0; therefore, the tens digit equals 2n + 0 = n (mod 10). The only possible one digit number for n in this case is 0. 00 as a two digit number does not work. <br>
<b>Case 2</b>: When we square n1, the total tens digit equals n * 1 + n * 1 = 2n + 1; therefore, the tens digit equals 2n + 1 = n (mod 10). Again, the only possible on digit number for n in this case is 0. 01 as a two digit number does not work.<br>
<b>Case 3</b>: When we square n5, the total tens digit equals 2 * 5n + 2; the two is added at the end as a carry in from the <b>2</b>5 at 5 * 5. Therefore, the tens digit equals 2 * 5n + 2 = n (mod 10). The only possible one digit number for n in this case is 2, which creates the number 25. However, our question asks for any numbers other then 25. <br>
<b>Case 4</b>: When we square n6, the total tens digit euqals 2 * 6n + 3; the three is added at the end as a carry in from the <b>3</b>6 at 6 * 6. Therefore, the tens digit equals 2 * 6n + 2 = n (mod 10). The only possible one digit number for this case is 7, which makes 76.
<br>Therefore, the answer to our original question is <b>76</b>.



</solution>
