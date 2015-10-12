---
layout: post
title:  "20150811 - Find the Missing Number **"
date:   2015-08-11 18:52:55
categories: NumberTheory
author: richardwsong
---
Areteem每日一题2015年8月11日

<problem>

2^29（2的29次方）是一个九位数，其中所有数位都不同。在不把它算出来的条件下，确定它在0到9中缺了哪一个数。
<p>
The number 2^29 (the 29th power of 2) is a nine-digit number, all of whose digits are distinct. Without computing the actual number, determine which of the ten digits (0 to 9) is missing.
</p>
</problem>


### Solution <button>Show / Hide</button>

<solution>

Let n be the missing digit of the 9 digit number. The sum of the digits of the number would be  (1 + 2 + 3 + 4 + ... + 9) - n or 45 - n. There is a rule that states that the sum of the digits of a number and the number itself if both divided by nine have a same remainder. We figure that \[n = 2^{29} = 8^9 \cdot 4 \equiv (-1)^9 \cdot 4 = -4 \equiv 5\pmod 9,\] Therefore, the remainder of 2^29 / 9 equals 5. We already have that the sum of the digits of 2^29 equals 45 - n. Therefore, because 2^29 and the sum of the digits of 2^29 have the same remainder when divided by 9, we can set up the congruence \[45 - n \equiv 5 \pmod 9\] Using some very simple computation, we figure that n = 4. Therefore, the digit that is missing from 0 to 9 in 2^29 is <b>4</b>.


</solution>

