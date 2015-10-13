---
layout: post
title:  "20150812 - Find the Original Number "
date:   2015-08-12 18:52:55
categories: NumberTheory
author: ev3commander
---
Areteem每日一题2015年8月12日


<problem>

一个数的个位数是2。如果把个位的2移到最高位前面，则新形成的数是原数的2倍。求原数。
<p>
The units digit of a given number is 2. If this units digit 2 is moved to the first digit to form a new number, the new number is twice the original number. Find the original number.

</problem>


### Solution <button>Show / Hide</button>

<solution>

Because the two is at the beginning of the new number the old number must have a one at the front. That means after the two in the new number there is also a one. After the one in the old number there has to be a zero so the rest of the number is valid since one is the largest whole number that goes into two twice. There is also a zero in the new number after the one because zero is the largest whole number that goes into zero twice. Since we left out a one, we add ten to thenumber we got, which is zero. So zero is actually ten. That means the next number is five. This logic follows for the rest of the digits in both of the numbers until the old number reaches a two which is when the number ends. The answer is 105263157894736842.

</solution>

