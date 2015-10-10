---
layout: post
title:  "20150805- Find How Many 9-digit Numbers"
date:   2015-08-05 18:52:55
categories: NumberTheory
author: Wyzdm
---

Use the three digits 1,2,3 to construct 9-digit numbers, using each of 1,2,3 at least once. How many such 9-digit numbers are there?



### Solution <button>Show / Hide</button>

<solution>

First find the number of total 9 digit numbers that can be created with no restrictions on the problem. Three digits can go in each slot so the total amount is $3^9$. To get the answer, I have to subtract the number of 9 digit numbers that don't use 1,2, and 3 at least once from the total amount which is $3^9$. To get that, I have to make two cases. The first being that I find all 9 digit numbers that use two of the digits. First I have to choose which two digits to use. There are three ways to do that. There are $2^9$ ways to put in those two digits into the 9 slots of the number. So case one has $3*2^9$ numbers total.Case two its all the numbers that use one digit. This can be done three ways. But remember that in case one case two actually got counted twice. So I have to add three instead of subtracting three so I don't overcount. Therefore, the answer is $3^9-3*2^9+3=18150$

</solution>

